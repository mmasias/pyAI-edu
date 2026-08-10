# Formación diferenciada: profesorado + alumnado

> Los dos tracks (profesorado / alumnado) amplían el [`módulo mínimo`](minimo.md) para audiencias distintas. El **track profesorado** no produce contenido nuevo: lo que necesita más allá del módulo mínimo ya vive en dos plantillas hermanas (casos límite del asistente de clasificación / revisión académica bajo indicio); esta sección es un índice. El **track alumnado** sí es contenido nuevo — ningún artefacto pyAI-edu estaba escrito desde la perspectiva del alumno, y esta sección traduce los cierres de P1 (defensa oral), P4 (régimen A/B/D), P5 (seis arquetipos de fraude) y P10 (categorías de indicio) a _"qué espera el alumno"_ y _"cómo cumplir cada régimen sin caer en fraude"_, sin reescribir lo que ya vive en las plantillas que el alumno recibe o firma.

## Track profesorado

Lo que el profesorado necesita más allá del [`módulo mínimo`](minimo.md) ya está documentado en dos plantillas hermanas — esta sección es un índice, no duplica contenido.

- **Verificación en casos límite** (especificación por actividad / multi-régimen por fase / mixtura B/D dentro del mismo trabajo): cubierto en el [asistente de clasificación A/B/D, § Casos límite](../plantillas/asistente-clasificacion-abd.md#casos-límite). Los tres casos están tipificados ahí con su resolución: declaración de excepción acotada a una subtarea en B, clasificación por fase cuando la asignatura cambia de régimen, y remisión a la tabla por sección de la plantilla de acuerdo de supervisión TFG/TFM para la mixtura dentro del mismo entregable.
- **Apertura y gestión de revisiones académicas** (protocolo de apertura, notificación al alumno, catálogo de evidencias, criterios de ejecución accesible, plantilla de decisión motivada, criterio de parada §7.9): cubierto en [Revisión académica bajo indicio (P10 / §7.5)](../plantillas/revision-academica.md). La pieza incluye texto modelo de notificación, definición operativa de microdefensa, distinción entre evaluación negativa (no aprendió) e indicio de fraude (defraudó), y el límite con el procedimiento disciplinario del Reglamento Académico y del Alumno.

Para profundizar en arquetipos de fraude y aplicación práctica de la regla de cautela §7.6 (detector = disparador, nunca prueba), ver el [`módulo mínimo`](minimo.md). Para la guía de dirección de TFG/TFM y la salvaguarda de proporcionalidad del cierre P10, ver la [`ampliación`](ampliacion.md).

## Track alumnado

Esta sección es la única pieza de pyAI-edu escrita desde el alumno. No reescribe las plantillas que el alumno ya recibe (la [consigna por régimen](../plantillas/consigna-abd.md), la [declaración de autoría](../plantillas/declaracion-autoria.md), la [declaración de uso de IA](../plantillas/declaracion-uso-ia.md)) sino que traduce los cierres del cribado a tres preguntas operativas: en qué régimen estoy y qué tengo que hacer, qué pasa si me llaman a una defensa oral, y dónde está la frontera entre uso admisible y fraude.

El principio que sostiene las tres preguntas es el mismo que motivó eliminar VERITAS en P1: _"el alumno debe poder explicar lo entregado"_. Si puedes explicar lo que entregas, las piezas del régimen cribado encajan sin esfuerzo añadido. Si no puedes explicarlo, ningún papeleo extra lo resuelve.

### En qué régimen estoy y qué tengo que hacer

El enunciado de cada actividad evaluada dice explícitamente en cuál de los tres regímenes (A / B / D) estás, con el texto que el profesorado copia de la plantilla de consigna. Las obligaciones del alumno varían por régimen:

| Régimen | Qué permite | Qué tienes que hacer |
|---|---|---|
| **A — sin IA** | Ningún uso de IA, en ninguna fase. Excepción: apoyos de accesibilidad previamente autorizados. | Firmar la [declaración de autoría](../plantillas/declaracion-autoria.md). |
| **B — IA como medio** | IA como herramienta; el trabajo se evalúa con independencia de la herramienta usada. | Firmar la declaración de autoría. Rellenar la [declaración de uso de IA](../plantillas/declaracion-uso-ia.md) (herramienta + finalidad + fase). Trabajar en el Doc compartido desde el primer día, no pegar un documento final. |
| **D — IA como objeto evaluado** | IA como objeto; lo que se evalúa es tu interacción con la herramienta (auditar, criticar, corregir, reconstruir). | Lo mismo que en B, con la trazabilidad pasiva **obligatoria** (no recomendada): el Doc compartido es parte de lo evaluable. Además, tienes que poder explicar y reconstruir todo el proceso de interacción con la IA. |

Lo que cambia entre B y D no es cuánta IA usas, sino **qué se evalúa**: en B se evalúa el producto (la IA es solo la herramienta), en D se evalúa cómo usaste la IA (la IA es el objeto). Si la consigna deja ambiguo en cuál estás, pregunta antes de empezar — después no se puede reclasificar.

### Qué esperar en una defensa oral

La defensa oral es la conversación que verifica autoría efectiva cuando hay un indicio documentado (categoría 1 / 2 / 3 de P10). La abre el profesor con cuatro preguntas que son andamiaje, no improvisación:

1. **¿Por qué este enfoque y no otro que descartaste?** — verifica que las decisiones del trabajo son tuyas.
2. **¿Puedes modificar esto en vivo, delante de mí?** — verifica que puedes operar lo que entregaste, no solo describirlo.
3. **¿Qué parte de lo entregado no sabrías reproducir sin la herramienta?** — verifica que distingues lo que hace la IA de lo que haces tú.
4. **Si aparece un error aquí, ¿lo detectas y corriges sin ayuda?** — verifica que el trabajo está a tu altura, no por encima de ella.

**Lo que SÍ se te puede pedir:** explicar decisiones, modificar fragmentos en vivo, reconocer qué partes dependen de la herramienta, corregir errores. La defensa puede ser la completa (las cuatro preguntas, una a la vez) o una microdefensa (una pregunta puntual sobre una decisión concreta), según el alcance del indicio.

**Lo que NO se te puede pedir:** un log reconstruido a mano de cada interacción con la IA, una declaración exhaustiva palabra por palabra, o responder todas las preguntas a la vez. La declaración de uso que firmaste ya deja constancia mínima (herramienta + finalidad + fase); la defensa es para verificar que lo declarado cuadra con lo que puedes explicar.

**Cómo prepararse:** la defensa no se prepara el día antes. Se prepara trabajando de forma que las decisiones del trabajo sean tuyas durante la elaboración: si pediste a la IA un análisis, lo revisaste y lo reescribiste con tu criterio (no solo lo aceptaste); si generaste código, lo entiendes y lo sabes modificar; si la IA te dio una estructura, la elegiste entre varias opciones. Trabajar en el Doc compartido desde el primer día ayuda — el histórico es tu evidencia de proceso, no un trámite.

**Defensa reactiva vs. defensa obligatoria:** en asignaturas ordinarias la defensa es reactiva (se abre solo bajo indicio, no a todos). En TFG/TFM/tesis es obligatoria por diseño académico, cubre la reconstrucción del proceso completo y la puedes esperar siempre — ver la [guía para dirección](ampliacion.md#pieza-a--guía-para-dirección-de-tfgtfmtesis) si tu caso es un TFG/TFM/tesis.

### Diferencia entre uso admisible y fraude

La frontera la marca el cierre de P5: _"los seis arquetipos son actos afirmativos del alumno, no síntomas observables ni omisiones ambiguas"_. Es decir, lo que convierte un uso en fraude no es que la IA haya estado involucrada (eso es normal en B/D), sino que tú hiciste algo activo para sustituir tu autoría, fabricar evidencia, desproporcionar el uso al régimen, evadir verificación, colusionar con otros, o inventar fuentes.

Los seis arquetipos desde el alumno (cómo NO caer en cada uno):

1. **Copia literal o sustitución completa.** No entregues trabajo hecho por IA en su totalidad o en secciones sustantivas. Si la IA redactó un párrafo y tú lo dejaste sin reelaboración crítica, eso es arquetipo 1 — aunque el resto del trabajo sea tuyo.
2. **Fabricación de evidencia de proceso.** No falsifiques el histórico del Doc compartido, no crees versiones intermedias artificiales después de terminado, no manipules timestamps. La evidencia de proceso es lo que sostiene el régimen D; falsearla es fabricar la base misma del régimen.
3. **Uso desproporcionado al régimen.** Si estás en B, la IA es medio (defendible y reconstruible); usar IA para análisis sustantivos no declarados cruza al régimen D sin estar declarado. Si te das cuenta en medio del trabajo, **corrige la declaración** — la declaración incompleta corregida no es fraude, es deuda que se resuelve conversando.
4. **Evasión activa de verificación.** No ocultes, no niegues el uso al ser preguntado, no inventes excusas si te piden el enlace del chat declarado. Si lo borraste o no lo tienes, dilo — la conversación posterior distingue evaluación negativa de fraude; la evasión activa sí es arquetipo.
5. **Colusión organizada.** No orquestes con otros alumnos la personalización de una misma salida para evadir detección por similitud. Trabajar juntos es legítimo; orquestar outputs individualizables para parecer autoría independiente no lo es.
6. **Falsificación de fuente.** No presentes IA como bibliografía o autoría humana (DOI inexistente, autores inventados, citas que la IA generó y tú no verificaste). Citar mal una fuente real es evaluación negativa; inventar la fuente es fraude.

**La diferencia clave entre evaluación negativa y fraude:** si no puedes defender el trabajo porque no lo aprendiste, eso es evaluación negativa (no aprendiste). Si además de no poder defenderlo hay un arquetipo claro (sustituiste, fabricaste, desproporcionaste, evadiste, colusionaste, falsificaste), eso es fraude (defraudaste). La conversación de defensa oral funda esa distinción, no el indicio que la disparó — el detector o la observación que generó la sospecha inicial nunca es prueba por sí mismo (regla de cautela §7.6 / P6).

**Si te llaman a defensa y no sabes algo:** dilo. La incapacidad de recordar o de explicar un detalle funda más preguntas o evaluación negativa, no automáticamente fraude. La honestidad sobre lo que no sabes es parte de la defensa; la evasión es lo que la convierte en problema.

## Fundamentos

- Cierre de [P1](../articulos/P1.md) (_"el alumno debe poder explicar lo entregado"_; guion de 4 preguntas) del cribado ([discussions/1](https://github.com/mmasias/pyAI-edu/discussions/1)).
- Cierre de [P4](../articulos/P4.md) (régimen A/B/D; A sin IA, B IA como medio, D IA como objeto evaluado).
- Cierre de [P5](../articulos/P5.md) (seis arquetipos de fraude: copia literal / fabricación evidencia / uso desproporcionado al régimen / evasión activa / colusión organizada / falsificación de fuente; función diagnóstica, actos afirmativos).
- Cierre de [P10](../articulos/P10.md) (tres categorías de indicio — producto / proceso / interacción; detector como disparador, nunca prueba, regla 4 con P6).
- Plantillas a las que el track alumnado remite sin duplicar: [`consigna-abd.md`](../plantillas/consigna-abd.md), [`declaracion-autoria.md`](../plantillas/declaracion-autoria.md), [`declaracion-uso-ia.md`](../plantillas/declaracion-uso-ia.md), [`guion-defensa-canonico.md`](../plantillas/guion-defensa-canonico.md).
- Track profesorado construido como índice a [`asistente-clasificacion-abd.md`](../plantillas/asistente-clasificacion-abd.md) (casos límite) y [`revision-academica.md`](../plantillas/revision-academica.md) (revisión académica bajo indicio), siguiendo el mismo patrón que [`minimo.md`](minimo.md) usó para las cuatro plantillas cotidianas.
