# Judicial Cooperation Analysis

**Project Overview:**

This project analyzes and presents the geographical application of the Brussels I Regulation and its recast, focusing on EU judicial cooperation law. It aims to map trends, identify jurisdictional patterns, and highlight cross-border litigation flows between EU member states.

**Objectives:**

- Analyze the geographical and temporal trends in the application of the Brussels I Regulation.
- Identify jurisdictional patterns and cross-border litigation flows.
- Provide future forecasts leveraging Bayesian analysis.

**Project Structure:**

```plaintext
judicial-cooperation-analysis/
├── conda_env/
│   └── environment.yml        # Conda environment configuration
├── data/
│   ├── raw/                   # Raw datasets (CSV, shapefiles, GeoJSON)
│   ├── processed/             # Cleaned and structured data
│   ├── visualization-ready/   # Data outputs for mapping
├── docs/                      # Research and methodologies
├── modules/                   # Python scripts for automation and analysis
│   ├── data_ingestion.py      # Data collection and cleaning
│   ├── analysis.py            # Analysis methods (e.g., clustering, APR)
│   ├── visualization.py       # Export maps and visuals
├── notebooks/                 # Jupyter notebooks for iterative analysis
├── outputs/
│   ├── maps/                  # Exported maps and images
│   ├── charts/                # Graphs for PowerPoint
├── scripts/
│   ├── branch_setup.ps1       # Automated Git branch creation
│   ├── deploy_visuals.ps1     # Batch export for PowerPoint
├── presentation/
│   └── slides.pptx            # Final PowerPoint file
├── .gitignore
├── README.md
└── requirements.txt           # Python dependencies
```

