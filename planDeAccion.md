# Plan de acción

## Contexto

El repositorio constituye la base de conocimiento y el banco de trabajo de un asistente para profesorado sobre IA en educación, anclado en el protocolo institucional de UNEATLANTICO (`UNEATLANTICO/ProtocoloCIAEP.pdf`, V9 de 28/07/26).

Estado: corpus documental consolidado en `docs/` (15 documentos activos, 2 históricos) y **cribado del protocolo V9 cerrado** ([discussions/1](https://github.com/mmasias/pyAI-edu/discussions/1)). El cribado sustituye la lectura literal del V9 por un mínimo operativo perenne, discutido punto por punto (P0-P10) con criterio explícito de qué se conserva y qué se retira. Este documento se actualiza a partir de ese resultado — las líneas de trabajo que siguen ya no citan instrumentos del V9 que el cribado eliminó (VERITAS, RICE, régimen C).

## Resultado del cribado (resumen para quien no siguió la discussion)

- **Régimen A/B/D** (no A/B/C/D): la distinción instrumental/conceptual/sustantivo colapsa a dos preguntas de diseño — ¿reconstruible sin la herramienta? y ¿la IA es medio o es el objeto evaluado? — que determinan mecánicamente el régimen (P3, P4).
- **Sin VERITAS ni RICE como instrumentos formales.** Se sustituyen por mecanismos reales: guion de defensa oral de 4 preguntas (P1) y trazabilidad pasiva (historial de versiones de Docs/Sheets u ecosistema Git, según infraestructura de la asignatura — P2, P8) con verificación activada por disparador, no universal.
- **Disparadores de verificación** definidos en tres categorías de indicio — producto, proceso, interacción — con registro estructurado de un clic, no texto libre (P10).
- **6 arquetipos de fraude**, abiertos y combinables, no una lista cerrada: copia literal/sustitución, fabricación de evidencia de proceso, uso desproporcionado al régimen, evasión activa de verificación, colusión organizada, falsificación de fuente (P5).
- **Regla de cautela §7.6 reforzada, no debilitada**: un detector automático puede ser disparador, nunca prueba. Es la pieza que sostiene que todo lo anterior se resuelva por juicio humano y no por delegación a una herramienta de puntuación (P6).
- **Régimen reforzado TFG/TFM/tesis** sin los 13 campos del V9: declaración en apartado metodológico, entrega escalonada, defensa oral final obligatoria (P7).

Material demostrativo asociado (no integrado en el asistente, referencia para construir demos): [discussions/2](https://github.com/mmasias/pyAI-edu/discussions/2) — dashboard real de trazabilidad de una asignatura con forks de Git, con DAFO.

## Líneas de trabajo

### 1. Núcleo de conocimiento del asistente

El resultado del cribado pasa a ser la **referencia operativa prioritaria** para cualquier consulta del profesorado de UNEATLANTICO; el corpus `docs/` sigue como marco contextual (normativa superior y orientaciones externas).

**Estructura de lectura en tres capas (P9):**
1. **Resumen operativo** (1 página): régimen A/B/D + regla de migración, guion de defensa oral, disparadores de verificación + trazabilidad pasiva, 6 arquetipos, regla de cautela. Único material que el profesorado necesita leer para actuar el primer día de curso.
2. **Artículos por punto** (uno por P0-P10, a partir del "Cierre del punto" ya cerrado en la discussion): para quien pregunta el porqué de una regla concreta.
3. **V9 completo, como política que autoriza y limita**, no como protocolo de consulta directa: referencia de última instancia para comité, dirección o auditoría.

**Contenido tentativo del resumen operativo (capa 1)**, a comprimir en 1 página:
régimen A/B/D + regla mecánica de migración · declaración de autoría · declaración de uso de IA · guion de defensa oral, presentado como sugerido con enlace a la versión canónica de línea 2 (ver deuda P1 más abajo) · 3 categorías de indicio · 6 arquetipos de fraude · regla de cautela §7.6 · cómo aplicarlo el primer día de curso.
Ubicación propuesta: `RESUMEN-OPERATIVO.md` en la raíz del repo, visible junto a `README.md` y este documento — no dentro de `docs/`, que es corpus normativo, no material operativo.

**Tareas de capa 1 y 2:**
- Redactar el resumen operativo (capa 1).
- Redactar los artículos de capa 2, uno por punto del cribado.
- Construir un glosario alineado con el vocabulario del cribado (reconstruible/medio-objeto, arquetipo, disparador, régimen A/B/D), no con las categorías del V9 que el cribado sustituyó.

**Tarea puente hacia la capa 3** (no es tarea de capa 1/2 — el cribado ya colapsó la mayoría del V9, este mapeo fino solo tiene sentido para leer el V9 como política, no como manual de aula):
- Mapear referencias cruzadas: AI Act anexo III (educación, alto riesgo) ↔ §2.3 del protocolo; GDPR arts. 5/6/9 ↔ §6; LOPDGDD ↔ §6; Directiva 2019/790 ↔ §4.4 sobre atribución de fuentes.

### 2. Plantillas operativas y módulo formativo mínimo

El protocolo cribado define principios y mecanismos pero no proporciona modelos listos para usar. **Se publican junto al módulo formativo mínimo, no antes** (P9, decisión estricta): unas plantillas sin manual de uso es exactamente el fallo del V9 que el cribado quiere evitar.

**Entregables (plantillas):**
- Plantilla de **Declaración de autoría** (válida para A/B/D).
- Plantilla de **Declaración de uso de IA** por régimen (B/D), con campos redefinidos tras el cribado: herramienta, finalidad, fase, disparador aplicable si lo hay — sin los campos de VERITAS ni de RICE.
- **Guion de defensa oral** (P1): sugerido como default en el resumen operativo, no impuesto — las 4 preguntas cubren bien producto de código/texto pero no están probadas en actuación, interpretación musical o cálculo manual; imponerlo como definitivo arriesga la misma fosilización que motivó retirar VERITAS. Se acompaña de una **versión canónica cerrada en anexo**, para el profesorado que prefiera un punto de partida fijo sin adaptarlo.
- **Registro estructurado de indicio** (P10): categoría + ejemplo concreto, un clic.
- Plantilla de **consigna tipo** por régimen (A/B/D), con la regla de especificación por actividad del §4.3.

**Módulo formativo mínimo (P9, las 4 piezas básicas, publicado con las plantillas de arriba):**
1. Declaración de autoría — qué es, cuándo se firma.
2. Declaración de uso de IA — cómo rellenarla por régimen.
3. Guion de defensa oral — cómo ejecutarlo (qué preguntar, qué escuchar, cómo interpretar la respuesta).
4. Consigna A/B/D — cómo redactarla con la regla de especificación por actividad.

El módulo se **amplía** tras la línea 4 (ver más abajo) con la parte que todavía no puede escribirse: TFG/TFM y la guía procedural de revisión del criterio del profesor (deuda P10).

### 3. Asistente de clasificación A/B/D

El profesorado necesita ayuda para dos decisiones de diseño:
- Clasificar una actividad en el régimen correcto (A/B/D), con la regla mecánica ya cerrada en el cribado (P3, P4).
- Redactar la consigna con las especificaciones exigidas.

**Entregables:**
- Árbol de decisión basado en las dos preguntas de P3 (¿reconstruible sin IA? ¿medio u objeto?), no en la taxonomía instrumental/conceptual/sustantivo del V9.
- Ejemplos por disciplina y tipo de actividad — ya hay un primer borrador de seis casos (Derecho, Ingeniería, Enfermería, Historia, Marketing, Matemáticas) en la discussion #1, cierre de P4; ampliar y llevar a plantilla.
- Casos límite documentados: especificación por actividad dentro de un régimen (§4.3), multi-régimen por fase dentro de la misma asignatura, mixtura B/D en un mismo trabajo (deuda P4, ver más abajo).

### 4. Caso especial TFG, TFM y tesis doctorales

Régimen reforzado sin los 13 campos del V9 (P7): declaración en apartado metodológico (no en anexo), entrega escalonada con versiones revisables por la dirección, defensa oral final obligatoria que cubre explícitamente la reconstrucción del proceso.

**Entregables:**
- Plantilla de **acuerdo de supervisión** que fija régimen (con la regla de P4) y expectativas desde el inicio. Esta plantilla resuelve dos deudas del cribado a la vez: la mixtura B/D dentro del mismo trabajo (deuda P4) y la distinción entre dirección activa y nominal a efectos de responsabilidad (deuda P7).
- Criterios para que la dirección/tutoría valore la trazabilidad antes del depósito.

Tras esta línea, se amplía el módulo formativo mínimo (línea 2) con la guía TFG/TFM y con la guía procedural que resuelve la deuda P10 (responsable de la revisión del criterio del profesor cuando un patrón de activación de indicios resulta desproporcionado).

### 5. Módulo de revisión académica

Herramienta para profesorado que recibe una entrega con indicios documentados (P10) o dudas razonables. Crítico para no cruzar la línea entre revisión académica y expediente disciplinario (§7).

**Entregables:**
- Protocolo de apertura de revisión académica conforme al §7.5, activado por el registro estructurado de indicio de P10 (no por texto libre).
- Catálogo de evidencias solicitables: versiones intermedias, trazabilidad pasiva, defensa oral, microdefensas.
- Plantilla de decisión motivada que distinga decisión evaluativa de eventual expediente disciplinario, y que distinga explícitamente evaluación negativa (no aprendió) de fraude (defraudó) — la misma distinción que motivó retirar el arquetipo tautológico original de P5.
- Recordatorio operativo de la **regla de cautela (§7.6 / P6)**: ningún detector de IA o similitud funda por sí solo una decisión; el registro de indicios es auditable y sujeto a revisión de proporcionalidad si se concentra sobre un mismo alumno sin confirmación.

### 6. Formación diferenciada

El grueso de la formación de profesorado ya queda cubierto por el módulo formativo mínimo de la línea 2 y su ampliación tras la línea 4. Esta línea se reduce a lo que no cabe ahí:

**Track profesorado (más allá del módulo mínimo):**
- Verificación de entregas en casos límite (mixturas, multi-régimen por fase).
- Apertura y gestión de revisiones académicas (línea 5).

**Track alumnado:**
- Cómo cumplir cada régimen.
- Cómo se activa una verificación y qué se espera en una defensa oral.
- Diferencia entre uso admisible y los arquetipos de P5.

**Entregables:** guías breves por track, ejemplos trabajados, casos resueltos.

### 7. Catálogo de herramientas autorizadas

El §6.4 y §6.11 exigen un inventario institucional. Esta línea resuelve la deuda P0 del cribado: el criterio de corte técnico (sobrevive a un modelo nuevo, a un agente autónomo, a otra modalidad) no distingue cláusulas que son transposición de norma legal externa (RGPD, AI Act — p. ej. §6.3, §6.4) de las que son diseño pedagógico interno del V9. Aquí es donde pyAI-edu decide qué responsabilidad de cumplimiento normativo asume.

**Tareas:**
- Definir esquema del catálogo: herramienta, versión, proveedor, finalidad autorizada, régimen compatible, restricciones RGPD/AI Act, fecha de revisión.
- Procedimiento de alta/baja de herramientas.
- Integración con el asistente de clasificación (línea 3): una herramienta no autorizada desencadena reclasificación de la actividad o exclusión del uso.

## Deudas del cribado y dónde se resuelven

Seis puntos del cribado (discussion #1) se cerraron con una deuda registrada — un flanco identificado que no reabre el punto pero que necesita resolución antes de que el entregable correspondiente se dé por completo.

| Deuda | Origen | Se resuelve en |
|---|---|---|
| **P0** — el criterio de corte mide robustez técnica, pero no distingue cláusulas de transposición legal externa de diseño pedagógico interno (§6 mezcla ambas) | Cierre de P0 | Línea 7 — catálogo de herramientas, donde se decide qué responsabilidad normativa asume pyAI-edu |
| **P1** — el guion de defensa oral quedó como sugerido, no canónico | Cierre de P1 | Línea 2 — plantillas: se mantiene sugerido como default en el resumen operativo, con versión canónica cerrada en anexo para quien la prefiera fija |
| **P3** — falta un tercer eje de diseño, "momento formativo" (fase del aprendizaje), sin desarrollar | Cierre de P3 | Línea 1, capa 2 — artículo dedicado a P3 |
| **P4** — falta resolver la mixtura B/D dentro del mismo trabajo (la IA es medio en una parte y objeto evaluado en otra) | Cierre de P4 | Línea 4 — plantilla de acuerdo de supervisión |
| **P7** — falta distinguir dirección activa de dirección nominal a efectos de responsabilidad | Cierre de P7 | Línea 4 — misma plantilla de acuerdo de supervisión |
| **P10** — falta definir quién revisa el criterio del profesor cuando el registro de indicios muestra activaciones repetidas sin confirmar | Cierre de P10 | Línea 2 (ampliación tras línea 4) — guía procedural del módulo formativo |

## Priorización

Orden revisado tras el cierre del cribado, con la decisión de publicar plantillas y módulo formativo mínimo juntos (P9 estricto):

1. **Línea 1, capa 1** — resumen operativo. Primer entregable; condición de entrada para todo lo demás, porque fija el vocabulario y las reglas mecánicas que el resto usa.
2. **Línea 1, capa 2** — artículos por punto (P0-P10), en paralelo o inmediatamente después.
3. **Línea 2** — plantillas operativas + módulo formativo mínimo, publicados juntos. No se publica una plantilla sin el módulo mínimo que enseña a usarla.
4. **Línea 3** — asistente de clasificación A/B/D, en paralelo a la línea 2; usa la regla mecánica ya cerrada.
5. **Línea 4** — TFG/TFM/tesis, plantilla de acuerdo de supervisión. Resuelve las deudas P4 y P7.
6. **Ampliación del módulo formativo** (línea 2/6) tras la línea 4 — incorpora TFG/TFM y resuelve la deuda P10.
7. **Línea 5** — módulo de revisión académica.
8. **Línea 7** — catálogo de herramientas. Resuelve la deuda P0.

## Criterios transversales

- **Idioma:** artefactos en español (convención del proyecto).
- **Registro:** técnico, sin jerga pedagógica ni corporativa.
- **Trazabilidad:** cada entregable cita el punto del cribado (P0-P10) o la sección de la norma que lo funda.
- **Versionado:** cambios en el protocolo (V10+) disparan revisión del cribado, no solo de las plantillas — el cribado es la capa intermedia que absorbe el cambio antes de que llegue al profesorado.
