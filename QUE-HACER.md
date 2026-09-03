# Qué hacer

## 0.a. Guía docente

En la guía docente ya está incluido lo siguiente:

> Esta asignatura se rige por el Protocolo de medidas para garantizar la calidad y la integridad académicas en la modalidad de enseñanza presencial de UNEATLANTICO. El régimen aplicable a cada actividad se indicará en su enunciado.

## 0.b. Recordar los regímenes con los que trabajamos

| Régimen A | Régimen B | Régimen D |
|---|---|---|
| Sin IA | IA como medio | IA como objeto evaluado |

## 1. Antes de cada actividad evaluable

### Fijar el régimen

Si no se permite IA en la actividad, el régimen es **A**. Si se permite, una pregunta distingue B de D: **¿se evalúa el resultado con independencia de cómo se haya producido, o el modo en que el alumno emplea la IA?**

| Régimen | Cuándo aplica | Qué se evalúa |
|---|---|---|
| **Sin IA (A)** | No se permite ninguna herramienta de IA (salvo apoyos de accesibilidad autorizados) | El trabajo, con independencia de cualquier herramienta |
| **IA como medio (B)** | La IA es un medio para producir el resultado | El resultado, con independencia de la herramienta empleada |
| **IA como objeto evaluado (D)** | La IA es aquello que se evalúa: auditar, criticar, corregir o reconstruir su salida | La interacción del alumno con la herramienta |

La distinción entre B y D no depende de cuánta IA se emplea, sino de qué se califica: el producto (B) o el uso de la herramienta (D).

### Redactar la consigna

Copiar en el enunciado de la actividad el bloque correspondiente al régimen fijado: [`docs/plantillas/consigna-abd.md`](docs/plantillas/consigna-abd.md).

Cuando se autoriza el uso de IA solo para una subtarea acotada (por ejemplo, traducir una fuente), esa excepción se declara en la consigna. No eleva el régimen de la actividad completa.

> Para esto puede apoyarse en las **[consignas predeterminadas](docs/plantillas/consigna-abd.md)** o utilizar el **[Asistente de redacción de consignas](tools/asistente-consignas-profesor.md)**.

## 2. Al recoger las entregas

| Régimen | Declaración de autoría | Declaración de uso de IA | Documento compartido |
|---|:-:|:-:|:-:|
| Sin IA (A) | Obligatoria | — | — |
| IA como medio (B) | Obligatoria | Obligatoria | Recomendado |
| IA como objeto evaluado (D) | Obligatoria | Obligatoria | Obligatorio |

- **Declaración de autoría**: una línea, en toda entrega. Plantilla: [`declaracion-autoria.md`](docs/plantillas/declaracion-autoria.md).
- **Declaración de uso de IA**: herramienta, finalidad y fase en que intervino. Plantilla: [`declaracion-uso-ia.md`](docs/plantillas/declaracion-uso-ia.md).
- **Documento compartido**: el trabajo se redacta en un documento compartido con el profesorado desde el primer día; no se entrega un documento pegado al final. El historial de versiones es el registro del proceso.

## 3. Si una entrega no cuadra

### Documentar el indicio

Registrar el indicio que motiva la verificación: una de tres categorías, con un ejemplo concreto y sin texto libre. Plantilla: [`registro-indicio.md`](docs/plantillas/registro-indicio.md).

| Categoría | Qué recoge |
|---|---|
| **Producto** | Lo entregado descuadra con el rendimiento previo del alumno o con el régimen asignado |
| **Proceso** | Huecos o incoherencias en el historial del documento compartido o en el enlace de chat |
| **Interacción** | El comportamiento en aula o tutoría no se corresponde con el trabajo entregado |

Un solo indicio documentado basta para activar la verificación. No se exige concurrencia de varios ni gravedad mínima.

### Verificar en conversación

La verificación es una conversación con el alumno, no una sanción. El guion, dirigido al alumno, lo ejecuta el profesor una pregunta cada vez y sin anticipar la respuesta:

> 1. ¿Por qué este enfoque y no otro que descartaste?
> 2. ¿Puedes modificar esto en vivo, delante de mí?
> 3. ¿Qué parte de lo entregado no sabrías reproducir sin la herramienta?
> 4. Si aparece un error aquí, ¿lo detectas y lo corriges sin ayuda?

Guion completo y reglas de ejecución: [`guion-defensa-canonico.md`](docs/plantillas/guion-defensa-canonico.md).

Antes de resolver, el alumno tiene derecho a conocer el indicio registrado, aportar evidencia y alegar. Notificación obligatoria y texto modelo: [`revision-academica.md`](docs/plantillas/revision-academica.md).

### Resolver a partir de la conversación

- **El alumno defiende el trabajo**: verificación cerrada sin consecuencia. Si el indicio procedía de un detector automático, se considera un falso positivo.
- **El alumno no sostiene el trabajo**: evaluación negativa, no acredita el aprendizaje. No constituye fraude por sí sola.
- **Concurre un acto de engaño** (copia literal o sustitución completa del trabajo, falsificación del historial de proceso, uso desproporcionado al régimen, evasión activa de la verificación, colusión organizada o falsificación de fuentes): procede adoptar la decisión evaluativa que corresponda, preservar toda la evidencia recabada sin alterarla (documento compartido, registro de indicio, plantilla de decisión motivada) y remitirla al órgano competente. La instrucción del expediente no corresponde al profesorado. Procedimiento y plantilla de decisión motivada: [`revision-academica.md`](docs/plantillas/revision-academica.md).

## Criterio

Un detector automático, de IA o de similitud, puede motivar una verificación. No la resuelve. Lo que funda la decisión es la conversación, nunca el indicio que la originó.

Si el registro muestra verificaciones reiteradas sobre un mismo alumno sin confirmación en ninguna conversación, se revisa el criterio del profesor, no al alumno.

## Ejemplos por grado

Un ejemplo de cada régimen por titulación. Clasificación razonada y casos límite: [Clasificación de actividades](docs/plantillas/asistente-clasificacion-abd.md).

### Ingeniería Informática

| Régimen | Actividad |
|---|---|
| **Sin IA (A)** | Prueba presencial de programación sin conexión: se evalúa escribir y razonar el código sin asistencia. |
| **IA como medio (B)** | Desarrollo de software con autocompletado o generación asistida por LLM: se evalúa el producto y su defensa en code review, con independencia de la herramienta. |
| **IA como objeto evaluado (D)** | Auditoría de código generado por un LLM: identificar y corregir errores, vulnerabilidades y malas prácticas en la salida del modelo; se evalúa la interacción con la herramienta. |

### Ingeniería de Organización Industrial

Asignatura Administración de la Producción y Logística.

| Régimen | Actividad |
|---|---|
| **Sin IA (A)** | Prueba presencial sobre planificación de la producción y gestión de inventarios (previsión de demanda, lote económico, stock de seguridad), sin asistencia; se evalúa el procedimiento y su justificación. |
| **IA como medio (B)** | Informe de rediseño de la red de distribución de una empresa (localización de almacenes, asignación de rutas), con IA para modelar escenarios y redactar; se evalúa la propuesta y su justificación económica, con independencia de la herramienta. |
| **IA como objeto evaluado (D)** | Auditoría de un plan maestro de producción propuesto por una IA a partir de una demanda y unas restricciones dadas: identificar y corregir supuestos incorrectos, restricciones de capacidad ignoradas y riesgos de rotura de stock; se evalúa la interacción con la herramienta. |

_Pendiente: ejemplos del resto de titulaciones, a partir de la aportación de cada dirección de grado._
