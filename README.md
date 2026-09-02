# pyAI-edu

Asistente para el profesorado sobre uso responsable de inteligencia artificial en el aula universitaria, anclado en el **Protocolo de medidas para garantizar la calidad y la integridad académicas** de UNEATLANTICO (V9, julio 2026).

## Qué leer primero

| Si quieres... | Lee |
|---|---|
| Saber qué hacer, sin explicaciones | [`QUE-HACER.md`](QUE-HACER.md) — hoja de acción, solo los pasos |
| Aplicar el régimen el primer día de curso, con el porqué de cada regla condensado | [`RESUMEN-OPERATIVO.md`](RESUMEN-OPERATIVO.md) — una página, todo lo operativo |
| Entender por qué una regla es como es | [`docs/articulos/`](docs/articulos/) — un artículo por punto del cribado (P0-P10) |
| Usar una plantilla ya lista (declaraciones, consigna, acuerdo TFG/TFM...) | [`docs/plantillas/`](docs/plantillas/) |
| Ver qué falta y en qué orden se construye | [`planDeAccion.md`](planDeAccion.md) |
| Consultar el corpus normativo (UE, España, AEPD, NIST, UNESCO...) | [`docs/README.md`](docs/README.md) |
| Leer el debate completo que originó todo esto | [discussions#1](https://github.com/mmasias/pyAI-edu/discussions/1) |

## Audiencia

Profesorado de UNEATLANTICO como usuario primario. Extensible a cualquier universidad española que adopte un esquema equivalente al reglamento europeo (AI Act) y a la normativa de protección de datos.

## Estado

El Protocolo V9 fue cribado punto por punto (P0-P10) en [discussions#1](https://github.com/mmasias/pyAI-edu/discussions/1) — cerrado. De ahí sale el vocabulario vigente: **régimen A/B/D** (no A/B/C/D), sin VERITAS ni RICE como instrumentos formales.

Resumen operativo y artículos de capa 2 ya construidos y mergeados. Plantillas operativas en construcción vía backlog de issues — ver [`planDeAccion.md`](planDeAccion.md) para las líneas de trabajo y los issues abiertos del repo para el estado vivo.

## Estructura

```
pyAI-edu/
├── QUE-HACER.md            Hoja de acción: los pasos, sin justificación
├── RESUMEN-OPERATIVO.md    Una página: aplicación práctica del régimen con su porqué
├── planDeAccion.md         Hoja de ruta y backlog
├── docs/
│   ├── articulos/          Por qué de cada regla (P0-P10)
│   ├── plantillas/         Artefactos listos para usar
│   ├── modulo-formativo/   Formación (módulo mínimo, ampliación, diferenciada)
│   ├── historicos/         Copia local de 2 documentos pre-2022 descatalogados
│   └── README.md           Catálogo del corpus — enlaces a orígenes oficiales
└── UNEATLANTICO/
    └── ProtocoloCIAEP.pdf   Protocolo institucional V9, referencia de última instancia
```
