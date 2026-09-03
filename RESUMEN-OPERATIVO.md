# Resumen operativo — pyAI-edu

## 1. Régimen A/B/D

Tres regímenes: A, B, D.

<div align="center">

| Régimen | Cuándo aplica | Cómo se evalúa |
|---|---|---|
| **A** | Sin IA permitida | Con independencia de cualquier herramienta |
| **B** | IA como medio | Con independencia de la herramienta usada para producir |
| **D** | IA como objeto evaluado | A través de la interacción del alumno con la IA |

</div>

**Regla mecánica de clasificación** — una pregunta clasificatoria al diseñar la actividad:

> ¿La IA es **medio** para producir el resultado, o es el **objeto** mismo que se evalúa?

- Evalúa con independencia de la herramienta → **B** (con declaración de uso).
- Evalúa a través de la interacción con la IA → **D**.
- Sin IA permitida → **A**.

**Pregunta diagnóstica complementaria:** _¿El resultado debe ser reconstruible por el alumno sin la herramienta?_ Si la respuesta es NO, sugiere fuertemente D (la actividad depende de la IA); la decisión final la da la pregunta clasificatoria anterior.

## 2. Instrumentos por régimen

<div align="center">

| Régimen | Declaración autoría | Declaración uso IA | Trazabilidad pasiva |
|---|:-:|:-:|---|
| A | ✓ | — | — |
| B | ✓ | ✓ | Recomendada |
| D | ✓ | ✓ | Obligatoria |

</div>

- **Declaración de autoría:** universal. Una línea, <2 min.
  - _Ejemplo: "Declaro que la entrega referenciada es producto de mi autoría efectiva."_
- **Declaración de uso de IA:** herramienta + finalidad + fase. No reconstruye log; deja constancia. <5 min.
  - _Ejemplo: "Herramienta: Claude Sonnet 5 · Finalidad: corrección ortográfica · Fase: revisión final."_
- **Trazabilidad pasiva:** el trabajo en régimen B/D se redacta en un **Doc compartido con el profesor desde el primer día**, nunca se pega un documento final. El historial de versiones de Docs/Sheets hace de registro sin coste adicional.
  - _Ejemplo: "Doc de Google Drive compartido con el profesor desde el día 1; historial de versiones visible."_

## 3. Guion de defensa oral

Cuatro preguntas para verificar autoría efectiva cuando hay indicio. Lo ejecuta el profesor; no lo rellena el alumno.

1. ¿Por qué este enfoque y no otro que descartaste?
2. ¿Puedes modificar esto en vivo, delante de mí?
3. ¿Qué parte de lo entregado no sabrías reproducir sin la herramienta?
4. Si aparece un error aquí, ¿lo detectas y lo corriges sin ayuda?

**Cubre bien** producto de código/texto (y, por extensión, cálculo manual). **No probado** en ejecución práctica en vivo (p. ej. prácticas de Gastronomía, ejecución técnica en Ciencias de la Actividad Física y del Deporte) — adaptar por disciplina.

Versión fija, para quien prefiera no adaptarlo: [`docs/plantillas/guion-defensa-canonico.md`](docs/plantillas/guion-defensa-canonico.md).

## 4. Disparadores de verificación

Tres categorías exhaustivas. **Un indicio documentado de cualquiera basta para activar** la verificación (guion de defensa oral).

<div align="center">

| Categoría | Qué detecta | Ejemplos |
|---|---|---|
| **1. Producto** | El trabajo entregado descuadra con lo esperable del alumno o del régimen | Salto cualitativo vs. histórico · Inconsistencia de estilo entre secciones · Calidad superior a la demostrada en aula · Declaración vacía, copiada o contradictoria |
| **2. Proceso** | Huecos en la trazabilidad pasiva (Docs, enlace de chat) | Documento sin histórico · Saltos temporales inconsistentes · Enlace de chat que no cuadra con la declaración · Versiones intermedias ausentes cuando el régimen las exige |
| **3. Interacción** | El comportamiento en aula/tutoría descuadra con el trabajo entregado | Respuestas evasivas a preguntas sobre el propio trabajo · Incapacidad de explicar decisiones que el trabajo presupone · Discrepancia entre lo que el alumno dice conocer y lo que puede operar en vivo |

</div>

- **Registro:** categoría + ejemplo concreto, un clic. No texto libre.
- **Naturaleza:** conversacional (guion de defensa oral), no sancionadora.
- **Lo que funda la decisión es la conversación, no el indicio.**

## 5. Seis arquetipos de fraude

1. Copia literal o sustitución completa de la producción del alumno.
2. Fabricación de evidencia de proceso (versiones intermedias falseadas, etc.).
3. Uso desproporcionado al régimen asignado (análisis de fondo generado por IA donde solo se permite como apoyo).
4. Evasión activa de mecanismos de verificación (ocultar, negar el uso cuando se pregunta).
5. Colusión organizada (varios alumnos personalizando la misma salida para evadir detección por similitud).
6. Falsificación de fuente (IA presentada activamente como bibliografía o autoría humana).

**Función diagnóstica, no detectiva:** el profesorado detecta el uso indebido por criterio propio; los arquetipos ayudan a **tipificar la magnitud**, no a detectar. Combinables — un fraude real puede ser multi-arquetipo. Lista no cerrada: el profesorado puede proponer tipificaciones adicionales.

## 6. Regla de cautela

> Un detector automático (de IA, de similitud, etc.) puede ser **disparador**, nunca **prueba**.

Lo que funda una decisión es la conversación que el indicio dispara, no el indicio mismo. Si el registro muestra activaciones repetidas sobre el mismo alumno sin confirmación, se revisa el **criterio del profesor**, no al alumno.

## Cómo aplicarlo el primer día de curso

1. **Guía docente:** ya lleva incluida la frase _"Esta asignatura se rige por el Protocolo de medidas para garantizar la calidad y la integridad académicas en la modalidad de enseñanza presencial de UNEATLANTICO. El régimen aplicable a cada actividad se indicará en su enunciado."_
2. **Para cada actividad evaluada:** fijar el régimen (A/B/D) usando la regla mecánica del apartado 1.
3. **Para B:** declaración de autoría + declaración de uso + Doc compartido recomendado. **Para D:** exige lo mismo, con Doc compartido obligatorio.
4. **Para B y D:** añadir la consigna predeterminada del régimen, con la regla de especificación por actividad.
5. **Anunciar al aula:** la verificación es **reactiva, no universal** — cualquiera puede ser auditado bajo indicio, pero el indicio nunca es prueba y la conversación sí funda la decisión.
