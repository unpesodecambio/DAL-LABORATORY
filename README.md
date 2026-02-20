# DAL-LABORATORY


geomarketing-project/
│
├── data_raw/
│   ├── demografico/
│   ├── economico/
│   ├── movilidad/
│
├── data_processed/
│
├── outputs/
│   ├── capas_intermedias/
│   └── resultados_finales/
│
├── notebooks/
│   ├── 01_perfil_demografico.ipynb
│   ├── 02_economico.ipynb
│   ├── 03_movilidad.ipynb
│   ├── 04_diagnostico_mercado.ipynb
│   ├── 05_ponderacion_inicial.ipynb
│   ├── 06_ponderacion_final.ipynb
│
├── src/
│   ├── utils.py
│   ├── limpieza.py
│   ├── ponderacion.py
│
├── environment.yml
└── README.md



INSUMOS (I) 
    ↓
Perfil Demográfico  → 
Económico            →  Diagnóstico Mercado/Demanda  →
Movilidad            → 
    ↓
Ponderación Inicial
    ↓
Ponderación Final
