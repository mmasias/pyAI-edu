# Clasificación de actividades

Árbol de decisión para fijar el régimen de una actividad **antes de escribir la consigna**.

## Árbol de decisión

**Paso 1 — ¿Se permite IA en esta actividad?**

- **No** → régimen **A**. Fin.
- **Sí** → paso 2.

**Paso 2 — Pregunta clasificatoria (decisiva): ¿la IA es medio para producir el resultado, o es el objeto mismo que se evalúa?**

- El resultado se evalúa **con independencia** de la herramienta usada para producirlo → **B**, con declaración de uso.
- El resultado se evalúa **a través de** la interacción del alumno con la IA → **D**.

**Paso 2b — Pregunta diagnóstica complementaria (no decide por sí sola): ¿el resultado debe ser reconstruible por el alumno sin la herramienta?**

- **Sí** → confirma B (o A, si además no se permite IA).
- **No** → sugiere fuertemente D, pero la decisión final la da el paso 2, modulada por el momento formativo:
  - **Cursos iniciales:** un "no" aquí es señal para reconsiderar si la actividad debería exigir A (la actividad todavía no puede depender de IA en esta fase de aprendizaje) en vez de subir directamente a D.
  - **Cursos finales:** un "no" bien justificado (p. ej. código generado y mantenido, no solo copiado) es compatible con B — es práctica profesional legítima, no un indicio de que deba pasar a D.

La pregunta clasificatoria (paso 2) es la que fija el régimen. La pregunta diagnóstica (paso 2b) y el momento formativo son criterio de apoyo para resolver los casos donde la respuesta del paso 2 no es evidente a primera vista.

## Tabla de ejemplos por grado

Seis grados reales de UNEATLANTICO, uno por facultad como mínimo, con los dos casos límite incluidos.

| Grado UNEATLANTICO | Actividad | ¿Reconstruible sin IA? | ¿IA medio u objeto? | Régimen |
|---|---|---|---|---|
| Ingeniería Informática | Módulo de software con autocompletado/generación asistida por LLM | Sí, exigible en code review | Medio | B |
| Ingeniería de Organización Industrial | IA como tutor de pistas en ejercicios de optimización en la práctica; examen final presencial sin IA | Sí en la práctica; N/A en el examen | Medio en la práctica | B en práctica, A en evaluación final (caso límite: multi-régimen por fase) |
| Psicología | Caso clínico simulado: el alumno audita y corrige un diagnóstico generado por IA | No — el ejercicio depende de que exista la salida de la IA para auditarla | Objeto | D |
| Nutrición Humana y Dietética | Informe dietético de un caso, IA usada para resumir bibliografía científica y estructurar el informe | Sí — el criterio clínico final es del alumno | Medio | B |
| Traducción y Enseñanza de Lenguas | Comentario de una fuente en lengua extranjera; IA permitida solo para traducir la fuente | Sí, salvo la traducción | Medio (uso acotado a una subtarea) | B, con excepción declarada por tarea (caso límite: especificación por actividad) |
| Publicidad y Relaciones Públicas | Evaluación crítica de una campaña publicitaria generada por IA (sesgos, errores de marca) | No — se evalúa el juicio sobre la salida, no una producción propia | Objeto | D |

Grados oficiales de UNEATLANTICO: [grados.uneatlantico.es](https://grados.uneatlantico.es/) — 15 grados en 3 facultades.

## Casos límite

Dos casos que la regla mecánica resuelve sin necesitar un cuarto régimen:

1. **Especificación por actividad** (fila Traducción y Enseñanza de Lenguas): un uso acotado a una subtarea concreta puede permitirse dentro de una actividad B por lo demás restringida. Se declara la excepción en la consigna, no se sube toda la actividad a un régimen distinto.
2. **Multi-régimen por fase** (fila Ingeniería de Organización Industrial): la misma asignatura puede tener régimen distinto en fases distintas (práctica en B, evaluación final en A). Cada fase se clasifica por separado con el mismo árbol.

Un tercer caso — la **mixtura B/D dentro del mismo trabajo** (la IA es medio en una parte y objeto evaluado en otra parte del *mismo* entregable, no en fases distintas) — no se resuelve con este árbol de clasificación por actividad completa. Se resuelve con la tabla de régimen por sección de la [plantilla de acuerdo de supervisión TFG/TFM](acuerdo-supervision-tfg-tfm.md#régimen-de-uso-de-ia), donde este tipo de mixtura aparece con más frecuencia.
