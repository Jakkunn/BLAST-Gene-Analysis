blast-gene-conservation/
│
├── README.md
├── LICENSE
├── .gitignore
├── blast-gene-conservation.Rproj
│
├── data/
│   ├── raw/
│   │   ├── human_tp53.fasta
│   │   ├── chimp_tp53.fasta
│   │   ├── mouse_tp53.fasta
│   │   └── ...
│   │
│   ├── blast_results/
│   │   ├── human_vs_chimp.txt
│   │   ├── human_vs_mouse.txt
│   │   └── ...
│   │
│   └── processed/
│       └── similarity_table.csv
│
├── scripts/
│   ├── 01_download_sequences.R
│   ├── 02_run_analysis.R
│   ├── 03_visualizations.R
│   └── 04_summary_statistics.R
│
├── figures/
│   ├── similarity_barplot.png
│   ├── heatmap.png
│   └── phylogenetic_tree.png
│
├── report/
│   ├── TP53_Comparative_Analysis.Rmd
│   └── TP53_Comparative_Analysis.pdf
│
└── docs/
    └── project_notes.md
