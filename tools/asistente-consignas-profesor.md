# Asistente de redacción de consignas

Herramienta para fijar el régimen de uso de IA de una actividad (A / B / D) y generar la consigna lista para pegar en el enunciado. Archivo único, sin conexión: se descarga [`asistente-consignas-profesor.html`](asistente-consignas-profesor.html) y se abre en el navegador.

## Cómo funciona, paso a paso

<div align="center">

![Paso 1: identificación de la actividad](../images/asistenteConsigna-001.png)

_**1. Identificación.** Asignatura, actividad y curso. El curso ajusta la propuesta de régimen: más restrictivo en primeros cursos, con más margen en los últimos._

![Paso 2: finalidad y desempeño](../images/asistenteConsigna-002.png)

_**2. Finalidad y desempeño.** Qué acredita la actividad y qué parte del trabajo debe ser del alumno aunque use IA. Este último campo pasa literal a la consigna._

![Paso 3: determinación del régimen](../images/asistenteConsigna-003.png)

_**3. Determinación del régimen.** Tres preguntas fijan el régimen: si se permite IA, si la IA es un medio o el objeto evaluado, y si el resultado debe ser reconstruible sin la herramienta. El asistente propone un régimen; la decisión final es del profesor._

![Paso 4: precisiones para esta actividad](../images/asistenteConsigna-004.png)

_**4. Precisiones (opcional).** Afina la consigna sin cambiar el régimen: usos de IA autorizados o excluidos, y —solo en régimen B— una subtarea acotada en la que se permite IA sin subir el régimen de toda la actividad._

![Paso 5: resultado](../images/asistenteConsigna-005.png)

_**5. Resultado.** Se generan la consigna (para el enunciado) y la ficha interna (para el archivo del profesor), editables. Descarga en Word o texto, o copia al portapapeles._

</div>

## Ejemplo de salida (régimen B, con especificación por actividad)

```
Esta actividad se desarrolla en régimen B: la IA se permite como medio para producir el resultado, no como objeto evaluado. El trabajo se evalúa con independencia de la herramienta usada para producirlo.

Son obligatorios:
- Declaración de autoría.
- Declaración de uso de IA: herramienta, finalidad y fase.
- Trazabilidad recomendada: el trabajo se redacta en un documento compartido con el profesorado desde el primer día; el historial de versiones hace de registro sin coste adicional.

La IA no puede sustituir la autoría efectiva: la aportación intelectual del alumno debe ser defendible y reconstruible. La declaración de uso no exime de esta exigencia; la reconstrucción puede pedirse en una defensa oral bajo indicio.

Precisiones para esta actividad:
- Debe ser propio del alumno, sin delegar en la herramienta: Diseño del modelo del dominio del escenario propuesto por la actividad

Especificación por actividad. Dentro de esta actividad se autoriza excepcionalmente el uso de IA para:
- Subtarea acotada: Diagrama de objetos a partir del diagrama de clases original
- Herramienta permitida para esa subtarea: LLM
- Fase en la que se aplica: Instanciación a partir de las clases de dominio
El resto de la actividad sigue en régimen B sin IA o con IA solo como medio ya declarado. La excepción no sube el régimen de la actividad entera.
```
