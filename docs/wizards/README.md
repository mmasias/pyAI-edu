# Wizards pre-cribado (archivo histórico — NO usar)

Estos dos HTML son el **primer intento** de aterrizar el Protocolo V9 en algo operable por el profesorado, de julio de 2026, **anterior al cribado**. Se conservan como evidencia del problema que el cribado resolvió: el Anexo A exigía completar 8 bloques por cada actividad de evaluación, inviable con carga docente normal, con el riesgo de que todo se marcara como régimen C por defecto o de que solo se aplicara en TFG/TFM.

- `wizard_regimen_ia.html` — determina el régimen y genera ficha + consigna (Anexo A).
- `wizard_declaracion_estudiante.html` — declaraciones de autoría y de uso de IA (Anexo B).

**No son la herramienta vigente.** Usan el modelo que el cribado retiró: cuatro regímenes A/B/C/D, taxonomía instrumental/conceptual/sustantivo, y VERITAS y RICE como instrumentos obligatorios.

Las herramientas vigentes están en [`tools/`](../../tools/):

- **[Asistente de redacción de consignas](../../tools/asistente-consignas-profesor.md)** (profesorado) — tres regímenes A/B/D, una pregunta de clasificación (medio/objeto), sin VERITAS ni RICE, consigna alineada con [`docs/plantillas/consigna-abd.md`](../plantillas/consigna-abd.md).
- **[Asistente de declaración de autoría y uso de IA](../../tools/asistente-declaracion-alumno.md)** (alumnado) — declaraciones alineadas con [`docs/plantillas/declaracion-autoria.md`](../plantillas/declaracion-autoria.md) y [`docs/plantillas/declaracion-uso-ia.md`](../plantillas/declaracion-uso-ia.md).

Recorrido de cómo se pasó de uno a otro: [discussions#35](https://github.com/mmasias/pyAI-edu/discussions/35).
