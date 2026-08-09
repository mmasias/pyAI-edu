# pyAI@edu

Asistente para el profesorado sobre uso responsable de inteligencia artificial en el aula universitaria, con anclaje operativo en el **Protocolo de medidas para garantizar la calidad y la integridad académicas** de UNEATLANTICO (versión 9, julio 2026).

## Propósito

Construir un sistema que ayude al profesorado a:

1. Entender el marco normativo y orientativo (europeo, español, autonómico) sobre IA en educación.
2. Operativizar el protocolo institucional de UNEATLANTICO en el diseño de actividades y en la verificación de entregas.
3. Clasificar actividades en los regímenes del protocolo (A/B/C/D) y producir las plantillas exigidas (declaraciones, RICE, VERITAS).
4. Formar alumnado y profesorado en uso declarado, trazable y críticamente validado de la IA.

## Audiencia

Profesorado de UNEATLANTICO como usuario primario. El corpus documental y los criterios son extensibles a cualquier universidad española que adopte un esquema equivalente al reglamento europeo (AI Act) y a la normativa de protección de datos.

## Estructura del repositorio

```
pyAI-edu/
├── README.md                  Este documento
├── planDeAccion.md            Hoja de ruta priorizada
├── docs/                      Corpus documental de referencia
│   ├── *.pdf                  15 documentos activos
│   └── historicos/            2 documentos obsoletos (pre-IA generativa)
└── UNEATLANTICO/
    ├── ProtocoloCIAEP.pdf     Protocolo institucional V9 (28/07/26)
    └── ProtocoloCIAEP.txt     Extracción en texto plano para indexado
```

## Corpus documental (`docs/`)

Agrupado por bloque temático. Todos los documentos están verificados como PDF válidos.

### Marco normativo Unión Europea
| Archivo | Referencia |
|---|---|
| `EU_2016_GDPR_Reglamento_679_ES.pdf` | Reglamento (UE) 2016/679, protección de datos personales |
| `EU_2022_DSA_Reglamento_2065_ES.pdf` | Reglamento (UE) 2022/2065, Digital Services Act |
| `EU_2024_AI_Act_Reglamento_1689_ES.pdf` | Reglamento (UE) 2024/1689, Ley de IA |
| `EU_2019_Directiva_790_PI_mercado_digital_ES.pdf` | Directiva (UE) 2019/790, propiedad intelectual en el mercado único digital |
| `EU_2025_DigComp_3.0_EN.pdf` | DigComp 3.0, marco europeo de competencia digital (5ª edición) |

### Marco normativo España
| Archivo | Referencia |
|---|---|
| `BOE_2018_LOPDGDD_LO_3_2018_consolidado.pdf` | Ley Orgánica 3/2018 (texto consolidado vigente) |
| `BOE_1996_TRLPI_RDLeg_1_1996_consolidado.pdf` | Texto refundido Ley Propiedad Intelectual (consolidado a 2022) |

### Protección de datos aplicada a IA
| Archivo | Referencia |
|---|---|
| `AEPD_2026_nota_tecnica_calidad_datos_IA_ES.pdf` | Nota técnica AEPD sobre calidad/exactitud/minimización en IA (julio 2026) |
| `AEPD_2022_guia_basica_anonimizacion.pdf` | Guía básica de anonimización |

### Estándar de gestión de IA
| Archivo | Referencia |
|---|---|
| `NIST_2023_AI_RMF_100-1_EN.pdf` | NIST AI Risk Management Framework (alternativa gratuita a ISO/IEC 42001) |

### Marco competencial y orientaciones para educación
| Archivo | Referencia |
|---|---|
| `OECD_2026_AI_literacy_framework_EN.pdf` | OECD, marco de alfabetización en IA para primaria y secundaria |
| `UNESCO_2024_marco_competencias_docentes_IA_ES.pdf` | UNESCO, marco de competencias docentes en IA |
| `UNESCO_2021_recomendacion_etica_IA_ES.pdf` | UNESCO, recomendación sobre ética de la IA |
| `INTEF_2024_guia_IA_ambito_educativo.pdf` | Guía INTEF-MEFP para el ámbito educativo |
| `GenCat_2024_IA_educacio_catala.pdf` | Orientaciones Generalitat de Catalunya |

### Históricos (`docs/historicos/`)
Documentos previos a la irrupción de la IA generativa (antes de noviembre 2022). Se conservan como contexto histórico, no como referencia operativa.
- `AEPD_2020_guia_centros_educativos.pdf`
- `UNESCO_2021_IA_educacion_guia_docente_ES.pdf`

## Marco operativo: Protocolo CIAEP

El **Protocolo de Medidas para Garantizar la Calidad y la Integridad Académicas** (`UNEATLANTICO/ProtocoloCIAEP.pdf`) es la referencia operativa prioritaria del asistente. Sustancia el reglamento europeo y la normativa de protección de datos en reglas concretas de aplicación en aula.

Núcleo del protocolo:

- **3 categorías funcionales de uso** de IA: instrumental, conceptual, sustantiva.
- **4 regímenes institucionales** por actividad: A (sin IA), B (instrumental), C (asistido), D (IA integrada como objeto evaluado).
- **4 instrumentos acumulativos**: declaración de autoría, declaración de uso de IA, método VERITAS, Registro de Interacción Crítica Escalonada (RICE).
- **3 salvaguardas**: los indicios automáticos no son prueba (regla de cautela 7.6); revisión académica, reclamación de calificación y expediente disciplinario son cauces separados; proporcionalidad y reconstrucción razonable del proceso como criterio rector.

El detalle del trabajo derivado está en `planDeAccion.md`.

## Estado

- Fase de constitución del corpus y análisis del marco normativo.
- Pendiente: desarrollo de plantillas operativas, módulo de clasificación A/B/C/D y materiales formativos (ver `planDeAccion.md`).

## Nota sobre derechos

Las leyes y reglamentos (Unión Europea, BOE) son de dominio público conforme a la exclusión del artículo 13 del TRLPI. Las publicaciones de AEPD, INTEF, UNESCO, OECD y NIST se distribuyen bajo licencias abiertas institucionales. Se conservan en este repositorio privado para uso docente e investigador con atribución a la fuente original.
