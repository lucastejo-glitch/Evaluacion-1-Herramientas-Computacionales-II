# Evaluacion-1-Herramientas-Computacionales-II
Repositorio para evaluacion 1 de carga-deflexión para una viga simplemente apoyada con carga puntual centrada.

## 1. Estructura del Repositorio
El repositorio está organizado dividiendo entradas, analisis, figuras y reporte tecnico en LaTeX.
```
├── README.md                 # Guía de reproducibilidad y documentación del proyecto
├── USO_IA.md                 # Declaración y verificación del uso de IA
├── data/                     # Entradas (archivos originales e intactos)
│   ├── datos_viga.csv        # Carga aplicada (kN) y deflexión medida (mm)
│   ├── parametros_viga.xlsx  # Geometría de la sección (b, h, L) y módulo E
│   └── esquema_viga.png      # Esquema estructural del caso de estudio
├── analysis/                 # Análisis numérico y transformaciones
│   └── analisis_viga.xlsx    # Planilla con el cálculo de I, deflexión teórica y diferencias
├── figures/                  # Salidas gráficas
│   └── carga_deflexion.png   # Gráfico Carga vs Deflexión (medido vs teórico)
└── report/                   # Salida del reporte técnico
    ├── main.tex              # Archivo LaTeX
    ├── referencias.bib       # Archivo BibTeX con referencia bibliográfica
    └── nota_tecnica.pdf      # Documento final compilado
```
## 2. Descripcion de entradas y Parametros
Los archivos de entrada se encuentran en la carpeta data/ los cuales se mantienen en su version original y se trabajaron en copias:

- data/datos_viga.csv: Tabla de ensayos con la carga P en kN y la deflexión medida en mm.
- data/parametros_viga.xlsx: Geometría del modelo:
  - Luz entre apoyos (L): 4 m
  - Ancho de la sección (b): 0.2 m
  - Altura de la sección (h): 0.4 m
  - Moódulo de elasticidad (E): 25 GPa = 25 x 10^6 kN/m^2
