# Resumen operativo — pyAI-edu

> Una página para que el profesorado opere el régimen de IA el primer día de curso.
> Para los _por qués_ de cada regla: [`docs/articulos/`](docs/articulos/) (capa 2) o la [discusión de cribado](https://github.com/mmasias/pyAI-edu/discussions/1).
> Para referencia institucional completa: [`UNEATLANTICO/ProtocoloCIAEP.pdf`](UNEATLANTICO/ProtocoloCIAEP.pdf) (V9, política que autoriza y limita este resumen).

---

## 1. Régimen A/B/D

Tres regímenes. No cuatro: el régimen C del V9 colapsa porque la distinción conceptual/sustantivo es fuzzy en LLMs actuales (P3, P4).

| Régimen | Cuándo aplica | Cómo se evalúa |
|---|---|---|
| **A** | Sin IA permitida | Con independencia de cualquier herramienta |
| **B** | IA como medio | Con independencia de la herramienta usada para producir |
| **D** | IA como objeto evaluado | A través de la interacción del alumno con la IA |

**Regla mecánica de clasificación (P3 + P4)** — dos preguntas al diseñar la actividad:

1. ¿El resultado debe ser reconstruible por el alumno sin la herramienta?
2. ¿La IA es **medio** para producir el resultado, o es el **objeto** mismo que se evalúa?

- Evalúa con independencia de la herramienta → **B** (con declaración de uso).
- Evalúa a través de la interacción con la IA → **D**.
- Sin IA permitida → **A**.

## 2. Instrumentos por régimen

| Régimen | Declaración autoría | Declaración uso IA | Trazabilidad pasiva |
|---|:-:|:-:|---|
| A | ✓ | — | — |
| B | ✓ | ✓ | Recomendada |
| D | ✓ | ✓ | Obligatoria |

- **Declaración de autoría** (§5.1, P0): universal. Una línea, <2 min.
- **Declaración de uso de IA** (P2): herramienta + finalidad + fase. No reconstruye log; deja constancia. <5 min.
- **Trazabilidad pasiva** (P8): el trabajo en régimen B/D se redacta en un **Doc compartido con el profesor desde el primer día**, nunca se pega un documento final. El historial de versiones de Docs/Sheets hace de registro sin coste adicional — es la base sobre la que se construyen los indicios de proceso.

## 3. Guion de defensa oral (P1) — sugerido

Cuatro preguntas para verificar autoría efectiva cuando hay indicio. Lo ejecuta el profesor; no lo rellena el alumno.

1. ¿Por qué este enfoque y no otro que descartaste?
2. ¿Puedes modificar esto en vivo, delante de mí?
3. ¿Qué parte de lo entregado no sabrías reproducir sin la herramienta?
4. Si aparece un error aquí, ¿lo detectas y lo corriges sin ayuda?

**Cubre bien** producto de código/texto. **No probado** en actuación, interpretación musical o cálculo manual — adaptar por disciplina.

_Marcado como **sugerido**, no canónico: imponerlo fijo arriesga la misma fosilización que motivó retirar VERITAS. Versión canónica cerrada como punto de partida fijo: [issue #7](https://github.com/mmasias/pyAI-edu/issues/7)._

## 4. Disparadores de verificación (P10)

Tres categorías exhaustivas. **Un indicio documentado de cualquiera basta para activar** la verificación (guion de defensa oral).

| Categoría | Qué detecta | Ejemplos |
|---|---|---|
| **1. Producto** | El trabajo entregado descuadra con lo esperable del alumno o del régimen | Salto cualitativo vs. histórico · Inconsistencia de estilo entre secciones · Calidad superior a la demostrada en aula · Declaración vacía, copiada o contradictoria |
| **2. Proceso** | Huecos en la trazabilidad pasiva (Docs, enlace de chat) | Documento sin histórico · Saltos temporales inconsistentes · Enlace de chat que no cuadra con la declaración · Versiones intermedias ausentes cuando el régimen las exige |
| **3. Interacción** | El comportamiento en aula/tutoría descuadra con el trabajo entregado | Respuestas evasivas a preguntas sobre el propio trabajo · Incapacidad de explicar decisiones que el trabajo presupone |

- **Registro:** categoría + ejemplo concreto, un clic. No texto libre.
- **Naturaleza:** conversacional (guion P1), no sancionadora.
- **Lo que funda la decisión es la conversación, no el indicio.**

## 5. Seis arquetipos de fraude (P5) — abierto y combinable

1. Copia literal o sustitución completa de la producción del alumno.
2. Fabricación de evidencia de proceso (versiones intermedias falseadas, etc.).
3. Uso desproporcionado al régimen asignado (sustantivo donde solo se permite instrumental).
4. Evasión activa de mecanismos de verificación (ocultar, negar el uso cuando se pregunta).
5. Colusión organizada (varios alumnos personalizando la misma salida para evadir detección por similitud).
6. Falsificación de fuente (IA presentada activamente como bibliografía o autoría humana).

**Función diagnóstica, no detectiva:** el docente detecta el uso indebido por criterio propio; los arquetipos ayudan a **tipificar la magnitud**, no a detectar. Combinables — un fraude real puede ser multi-arquetipo. Lista no cerrada: el docente puede proponer tipificaciones adicionales.

## 6. Regla de cautela §7.6 (P6)

> Un detector automático (de IA, de similitud, etc.) puede ser **disparador**, nunca **prueba**.

Lo que funda una decisión es la conversación que el indicio dispara, no el indicio mismo. Si el registro muestra activaciones repetidas sobre el mismo alumno sin confirmación, se revisa el **criterio del profesor**, no al alumno.

Esta regla aparece al pie de cada plantilla operativa que toque verificación — es la pieza que sostiene que todo lo anterior se resuelva por juicio humano y no por delegación a una herramienta de puntuación.

---

## Cómo aplicarlo el primer día de curso

1. **Guía docente:** añadir la frase _"Esta asignatura se rige por el Protocolo CIAEP de UNEATLANTICO. El régimen aplicable a cada actividad se indicará en su enunciado."_
2. **Para cada actividad evaluada:** fijar el régimen (A/B/D) usando la regla mecánica de §1.
3. **Para B y D:** exigir declaración de autoría + declaración de uso + Doc compartido desde el primer día.
4. **Para D:** añadir consigna tipo con la regla de especificación por actividad (§4.3).
5. **Anunciar al aula:** la verificación es **reactiva, no universal** — cualquiera puede ser auditado bajo indicio, pero el indicio nunca es prueba y la conversación sí funda la decisión.

---

## Trazabilidad de este documento

- Fundado en el [cribado del V9 cerrado](https://github.com/mmasias/pyAI-edu/discussions/1) (P0-P10).
- Construido en [issue #3](https://github.com/mmasias/pyAI-edu/issues/3) y validado por revisión cruzada Claude + z.AI + usuario.
- Cambios en el protocolo V9 (V10+) disparan revisión del cribado, no directa de este documento — el cribado es la capa intermedia que absorbe el cambio.
