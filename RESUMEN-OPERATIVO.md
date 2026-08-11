# Resumen operativo — pyAI-edu

Las seis piezas en una página: qué **régimen** aplica a cada actividad, qué **instrumento** exige cada régimen con ejemplo, el **guion para verificar autoría** cuando hay indicio, **qué dispara** esa verificación, los **patrones de fraude** para tipificar lo encontrado y la **regla que impide delegar el criterio** a un detector automático.

> ||
> |-
> |<sub>Si busca la secuencia paso a paso para el primer día de clase, vaya directamente a [`Cómo aplicarlo`](#cómo-aplicarlo-el-primer-día-de-curso).
> |<sub>Para los _por qués_ de cada regla: [`docs/articulos/`](docs/articulos/) (capa 2) o la [discusión de cribado](https://github.com/mmasias/pyAI-edu/discussions/1).
> |<sub>Para formación sobre la ejecución (reconocimiento de arquetipos de fraude, aplicación práctica de la regla de cautela §7.6): [`docs/modulo-formativo/minimo.md`](docs/modulo-formativo/minimo.md).
> |<sub>Para referencia institucional completa: [`UNEATLANTICO/ProtocoloCIAEP.pdf`](UNEATLANTICO/ProtocoloCIAEP.pdf) — _Protocolo de medidas para garantizar la calidad y la integridad académicas en la modalidad de enseñanza presencial_, V9, política que autoriza y limita este resumen.

## 1. Régimen A/B/D

Tres regímenes. No cuatro: el régimen C del protocolo V9 colapsa porque la distinción conceptual/sustantivo es difusa en LLMs actuales ([P3](docs/articulos/P3.md#por-qué), [P4](docs/articulos/P4.md#por-qué)).

<div align="center">

| Régimen | Cuándo aplica | Cómo se evalúa |
|---|---|---|
| **A** | Sin IA permitida | Con independencia de cualquier herramienta |
| **B** | IA como medio | Con independencia de la herramienta usada para producir |
| **D** | IA como objeto evaluado | A través de la interacción del alumno con la IA |

</div>

**Regla mecánica de clasificación ([P3](docs/articulos/P3.md#qué-se-decidió) + [P4](docs/articulos/P4.md#qué-se-decidió))** — una pregunta clasificatoria al diseñar la actividad:

> ¿La IA es **medio** para producir el resultado, o es el **objeto** mismo que se evalúa?

- Evalúa con independencia de la herramienta → **B** (con declaración de uso).
- Evalúa a través de la interacción con la IA → **D**.
- Sin IA permitida → **A**.

**Pregunta diagnóstica complementaria ([P3](docs/articulos/P3.md#qué-se-decidió)):** _¿El resultado debe ser reconstruible por el alumno sin la herramienta?_ Si la respuesta es NO, sugiere fuertemente D (la actividad depende de la IA); la decisión final la da la pregunta clasificatoria anterior.

## 2. Instrumentos por régimen

<div align="center">

| Régimen | Declaración autoría | Declaración uso IA | Trazabilidad pasiva |
|---|:-:|:-:|---|
| A | ✓ | — | — |
| B | ✓ | ✓ | Recomendada |
| D | ✓ | ✓ | Obligatoria |

</div>

- **Declaración de autoría** (§5.1, [P0](docs/articulos/P0.md#qué-se-decidió)): universal. Una línea, <2 min.
  - _Ejemplo: "Declaro que la entrega referenciada es producto de mi autoría efectiva."_
- **Declaración de uso de IA** ([P2](docs/articulos/P2.md#qué-se-decidió)): herramienta + finalidad + fase. No reconstruye log; deja constancia. <5 min.
  - _Ejemplo: "Herramienta: Claude Sonnet 5 · Finalidad: corrección ortográfica · Fase: revisión final."_
- **Trazabilidad pasiva** ([P8](docs/articulos/P8.md#qué-se-decidió)): el trabajo en régimen B/D se redacta en un **Doc compartido con el profesor desde el primer día**, nunca se pega un documento final. El historial de versiones de Docs/Sheets hace de registro sin coste adicional — es la base sobre la que se construyen los indicios de proceso.
  - _Ejemplo: "Doc de Google Drive compartido con el profesor desde el día 1; historial de versiones visible."_

> _Nota de fidelidad al cribado: la distinción Recomendada(B)/Obligatoria(D) es inferencia de este resumen, no del [cierre de P8](docs/articulos/P8.md#qué-se-decidió). El cierre de P8 hablaba de "régimen C/D" sin diferenciar B de D. La inferencia es razonable (en D la trazabilidad es parte de lo evaluable; en B el producto se puede evaluar aparte), pero no debe citarse como si viniera de P8._

## 3. Guion de defensa oral ([P1](docs/articulos/P1.md#qué-se-decidió)) — sugerido

Cuatro preguntas para verificar autoría efectiva cuando hay indicio. Lo ejecuta el profesor; no lo rellena el alumno.

1. ¿Por qué este enfoque y no otro que descartaste?
2. ¿Puedes modificar esto en vivo, delante de mí?
3. ¿Qué parte de lo entregado no sabrías reproducir sin la herramienta?
4. Si aparece un error aquí, ¿lo detectas y lo corriges sin ayuda?

**Cubre bien** producto de código/texto (y, por extensión, cálculo manual). **No probado** en ejecución práctica en vivo (p. ej. prácticas de Gastronomía, ejecución técnica en Ciencias de la Actividad Física y del Deporte) — adaptar por disciplina.

_Marcado como **sugerido**, no canónico: una versión fija arriesga fosilización — la misma razón por la que el cribado sustituyó VERITAS por este guion. Versión canónica cerrada como punto de partida fijo: [issue #7](https://github.com/mmasias/pyAI-edu/issues/7)._

## 4. Disparadores de verificación ([P10](docs/articulos/P10.md#qué-se-decidió))

Tres categorías exhaustivas. **Un indicio documentado de cualquiera basta para activar** la verificación (guion de defensa oral).

<div align="center">

| Categoría | Qué detecta | Ejemplos |
|---|---|---|
| **1. Producto** | El trabajo entregado descuadra con lo esperable del alumno o del régimen | Salto cualitativo vs. histórico · Inconsistencia de estilo entre secciones · Calidad superior a la demostrada en aula · Declaración vacía, copiada o contradictoria |
| **2. Proceso** | Huecos en la trazabilidad pasiva (Docs, enlace de chat) | Documento sin histórico · Saltos temporales inconsistentes · Enlace de chat que no cuadra con la declaración · Versiones intermedias ausentes cuando el régimen las exige |
| **3. Interacción** | El comportamiento en aula/tutoría descuadra con el trabajo entregado | Respuestas evasivas a preguntas sobre el propio trabajo · Incapacidad de explicar decisiones que el trabajo presupone · Discrepancia entre lo que el alumno dice conocer y lo que puede operar en vivo |

</div>

- **Registro:** categoría + ejemplo concreto, un clic. No texto libre.
- **Naturaleza:** conversacional (guion P1), no sancionadora.
- **Lo que funda la decisión es la conversación, no el indicio.**

## 5. Seis arquetipos de fraude ([P5](docs/articulos/P5.md#qué-se-decidió)) — abierto y combinable

1. Copia literal o sustitución completa de la producción del alumno.
2. Fabricación de evidencia de proceso (versiones intermedias falseadas, etc.).
3. Uso desproporcionado al régimen asignado (sustantivo donde solo se permite instrumental).
4. Evasión activa de mecanismos de verificación (ocultar, negar el uso cuando se pregunta).
5. Colusión organizada (varios alumnos personalizando la misma salida para evadir detección por similitud).
6. Falsificación de fuente (IA presentada activamente como bibliografía o autoría humana).

**Función diagnóstica, no detectiva:** el docente detecta el uso indebido por criterio propio; los arquetipos ayudan a **tipificar la magnitud**, no a detectar. Combinables — un fraude real puede ser multi-arquetipo. Lista no cerrada: el docente puede proponer tipificaciones adicionales.

## 6. Regla de cautela §7.6 ([P6](docs/articulos/P6.md#qué-se-decidió))

> Un detector automático (de IA, de similitud, etc.) puede ser **disparador**, nunca **prueba**.

Lo que funda una decisión es la conversación que el indicio dispara, no el indicio mismo. Si el registro muestra activaciones repetidas sobre el mismo alumno sin confirmación, se revisa el **criterio del profesor**, no al alumno.

Esta regla aparece al pie de cada plantilla operativa que toque verificación — es la pieza que sostiene que todo lo anterior se resuelva por juicio humano y no por delegación a una herramienta de puntuación.

## Cómo aplicarlo el primer día de curso

1. **Guía docente:** añadir la frase _"Esta asignatura se rige por el Protocolo de medidas para garantizar la calidad y la integridad académicas en la modalidad de enseñanza presencial de UNEATLANTICO. El régimen aplicable a cada actividad se indicará en su enunciado."_
2. **Para cada actividad evaluada:** fijar el régimen (A/B/D) usando la regla mecánica de §1.
3. **Para B:** declaración de autoría + declaración de uso + Doc compartido recomendado. **Para D:** exige lo mismo, con Doc compartido obligatorio.
4. **Para B y D:** añadir consigna tipo con la regla de especificación por actividad (§4.3).
5. **Anunciar al aula:** la verificación es **reactiva, no universal** — cualquiera puede ser auditado bajo indicio, pero el indicio nunca es prueba y la conversación sí funda la decisión.

## Trazabilidad de este documento

- Fundado en el [cribado del protocolo cerrado](https://github.com/mmasias/pyAI-edu/discussions/1) (P0-P10).
- Construido en [issue #3](https://github.com/mmasias/pyAI-edu/issues/3); este borrador está en revisión cruzada (Claude + z.AI + usuario) en [PR #17](https://github.com/mmasias/pyAI-edu/pull/17). La mención a validación aplica tras merge.
- Cambios en el protocolo (V10+) disparan revisión del cribado, no directa de este documento — el cribado es la capa intermedia que absorbe el cambio.
