# Plan de acción

## Contexto

El repositorio constituye la base de conocimiento y el banco de trabajo de un asistente para profesorado sobre IA en educación, anclado en el protocolo institucional de UNEATLANTICO (`UNEATLANTICO/ProtocoloCIAEP.pdf`, V9 de 28/07/26).

Estado inicial: corpus documental consolidado en `docs/` (15 documentos activos, 2 históricos) y protocolo interiorizado. Falta aterrizar el protocolo en herramientas, plantillas y materiales utilizables por el profesorado desde el primer día de curso.

## Líneas de trabajo

### 1. Núcleo de conocimiento del asistente

El protocolo CIAEP pasa a ser la **referencia operativa prioritaria** para cualquier consulta del profesorado de UNEATLANTICO. El corpus `docs/` queda como marco contextual (normativa superior y orientaciones externas).

**Tareas:**
- Indexar el texto del protocolo (`UNEATLANTICO/ProtocoloCIAEP.txt`) para consulta por secciones.
- Mapear referencias cruzadas: AI Act anexo III (educación, alto riesgo) ↔ §2.3 del protocolo; GDPR arts. 5/6/9 ↔ §6; LOPDGDD ↔ §6; Directiva 2019/790 ↔ §4.4 sobre atribución de fuentes.
- Construir un glosario alineado con las definiciones operativas del §1.5 del protocolo (autoría efectiva, usos instrumental/conceptual/sustantivo, VERITAS, RICE, trazabilidad, indicio automatizado, revisión académica).

### 2. Plantillas operativas

El protocolo menciona instrumentos pero no proporciona modelos listos para usar. El profesorado los necesita para aplicar el régimen desde el día 1.

**Entregables:**
- Plantilla de **Declaración de autoría** (valida para A/B/C/D).
- Plantilla de **Declaración de uso de IA** por régimen (B/C/D), con los campos mínimos del §5.2: herramienta y versión, finalidad, fase, operación, alcance, supervisión VERITAS, existencia de RICE.
- Plantilla **RICE sintético** (régimen B) y **RICE detallado** (régimenes C/D), con los 13 campos mínimos del §5.4.
- **Checklist VERITAS** por régimen (básico para B, íntegro para C/D), operacionalizando las 7 dimensiones (V-E-R-I-T-A-S).
- Plantilla de **consigna tipo** por régimen, con la regla de especificación por actividad del §4.3.

### 3. Asistente de clasificación A/B/C/D

El profesorado necesita ayuda para dos decisiones de diseño:
- Clasificar una actividad en el régimen correcto (A/B/C/D).
- Redactar la consigna con las especificaciones exigidas.

**Entregables:**
- Árbol de decisión basado en (a) competencias evaluadas, (b) naturaleza del producto, (c) fase del aprendizaje, (d) intención pedagógica respecto a la IA.
- Ejemplos por disciplina y tipo de actividad (examen presencial, trabajo corto, proyecto, defensa, TFG/TFM).
- Casos límite documentados: cuándo un uso sustantivo es admisible en régimen C (cuando la actividad audita IA, §4.2), cuándo reclasificar de B a C.

### 4. Caso especial TFG, TFM y tesis doctorales

El §5.4 prevé RICE reforzado y declaración en apartado metodológico (no en anexo). Requiere flujo propio por varias razones: supervisión extendida, acuerdo inicial con dirección, versiones sucesivas, defensa final.

**Entregables:**
- Flujo completo TFG/TFM/tesis: acuerdo inicial, tutorías con revisión de versiones, iteraciones relevantes, validación crítica, decisiones autorales, depósito y defensa.
- Plantilla de **acuerdo de supervisión** que fija régimen y expectativas.
- Criterios para que la dirección/tutoría valore la trazabilidad antes del depósito.

### 5. Módulo de revisión académica

Herramienta para profesorado que recibe una entrega con indicios o dudas razonables. Crítico para no cruzar la línea entre revisión académica y expediente disciplinario (§7).

**Entregables:**
- Protocolo de apertura de revisión académica conforme al §7.5 (notificación clara, causa, elementos en duda, documentación a aportar, plazo).
- Catálogo de evidencias solicitables: versiones intermedias, RICE, registros de interacción, defensas orales, microdefensas, entrevistas.
- Plantilla de decisión motivada que distinga decisión evaluativa de eventual expediente disciplinario.
- Recordatorio operativo de la **regla de cautela (§7.6)**: ningún detector de IA o similitud funda por sí solo una decisión.

### 6. Formación diferenciada

Dos tracks con objetivos distintos:

**Track profesorado:**
- Diseño de actividades por régimen.
- Redacción de consignas especificando régimen, herramientas permitidas/excluidas, fases, consecuencias.
- Verificación de entregas (qué mirar en un RICE, cómo auditar VERITAS).
- Apertura y gestión de revisiones académicas.

**Track alumnado:**
- Cómo cumplir cada régimen sin incurrir en prohibición transversal (§4.4).
- Cómo documentar un RICE sintético y detallado.
- Cómo aplicar VERITAS en la práctica.
- Diferencia entre uso admisible y los 10 supuestos prohibidos del §4.4.

**Entregables:** guías breves por track, ejemplos trabajados, casos resueltos.

### 7. Catálogo de herramientas autorizadas

El §6.4 y §6.11 exigen un inventario institucional. El asistente debe consultar el estado de autorización antes de recomendar cualquier herramienta.

**Tareas:**
- Definir esquema del catálogo: herramienta, versión, proveedor, finalidad autorizada, régimen compatible, restricciones RGPD/AI Act, fecha de revisión.
- Procedimiento de alta/baja de herramientas.
- Integración con el módulo de clasificación A/B/C/D (una herramienta no autorizada desencadena reclasificación de la actividad o exclusión del uso).

## Priorización

Orden propuesto para aterrizar valor en el primer cuatrimestre:

1. **Líneas 2 + 3 en paralelo** (plantillas operativas + asistente de clasificación). Son los entregables que el profesorado necesita desde el primer día; sin ellos el protocolo no aterriza en el aula.
2. **Línea 1** simultáneamente, porque indexa el conocimiento sobre el que se construyen las demás.
3. **Línea 6** (formación alumnado) en cuanto existan las plantillas, para que el alumnado las encuentre al inicio del curso.
4. **Líneas 4 y 5** en segunda oleada, dado que afectan a menos actividades pero requieren más madurez del sistema.
5. **Línea 7** cuando se confirme el procedimiento institucional de autorización de herramientas.

## Criterios transversales

- **Idioma:** artefactos en español (convención del proyecto).
- **Registro:** técnico, sin jerga pedagógica ni corporativa.
- **Trazabilidad:** cada entregable cita la sección del protocolo o la norma que lo funda.
- **Versionado:** cambios en el protocolo (V10+) disparan revisión de plantillas y ejemplos.
