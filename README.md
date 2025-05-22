# Anàlisi i visualització de la qualitat de l'aire a Barcelona

Aquest repositori conté el Treball Final de Màster (TFM) orientat a analitzar i visualitzar la qualitat de l'aire a la ciutat de Barcelona, utilitzant dades obertes, anàlisi estadística amb R i eines de geovisualització com ArcGIS Online.

## Objectiu

Analitzar l'evolució espaciotemporal de la contaminació atmosfèrica a Barcelona i relacionar-la amb variables meteorològiques, de mobilitat i morfologia urbana. Es treballa principalment amb quatre contaminants:

- NO₂ (diòxid de nitrogen)
- PM₁₀ (partícules en suspensió) 
- PM₂.₅ (partícules fines) 
- O₃ (ozó troposfèric)

## Estructura del repositori

```plaintext
TFM-qualitat-aire-barcelona/
├── data/
│   ├── raw/                     # Dades originals (XVPCA, XEMA, metadades)
│   └── processed/               # Dades tractades i preparades per a visualització
│       ├── contaminants/        # Dades de qualitat de l'aire processades
│       └── meteorologia/        # Dades meteorològiques processades
├── notebooks/
│   ├── 01_preprocessament_dades_qualitat_aire_Barcelona.Rmd    
│   ├── 02_analisis_exploratiu.Rmd
│   └── 03_model_predictiu_contaminant_NO2.Rmd              
├── docs/
│   ├── entregables/                 # Entregables del TFM
│   ├── notebooks_pdf/               # Versions PDF dels notebooks RMarkdown
│   ├── captures_visor/              # Captures de pantalla del visor fet en AGOL Dashboard
│   └── presentacio/                 # Diapositives per a la defensa
├── visor/
│   └── estructura_dashboard.md  # Esquema i configuració del visor a ArcGIS Online
├── planificacio_gantt.pdf       # Planificació del projecte
├── README.md                    # Descripció del projecte
└── .gitignore 
```


## Visor Web

Accés al visor interactiu publicat a ArcGIS Online:
[Pendent de fer-lo públic]


## Repositori

Aquest repositori inclou totes les dades processades, scripts d'anàlisi i documentació del projecte.
