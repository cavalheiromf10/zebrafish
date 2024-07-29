# Zebrafish

## Orthologous Protein Identification

- [X] Run OrthoFinder to find orthologs between zebrafish and humans.
- [ ] Separate identified proteins by chromosome and conservation index.

## Protein Characterization

### Calculate alignment variables for each ortholog:
-  % amino acid identity
-  % similar/positive amino acids
-  % coverage
-  E-value

## Functional Profile Analysis

### Use GO to analyze biological process, molecular function, and cellular component.
-  Use KEGG to identify pathways.
-  Use SignalP to identify signal peptides.

## Target Selection in Epilepsy

### Identify canonical orthologous proteins involved in epileptic seizures in zebrafish.
-  Level of conservation
-  Function (biological, molecular, cellular)
-  Involved pathways
-  Signal peptides
-  Type of orthology (one-to-one, one-to-two, one-to-more)

### Paralogous Analysis
-  Calculate alignment variables for duplicates.

## Structure

```bash
/zebrafish
│
├── /data
│   ├── /raw
│   │   └── orthofinder_output.zip
│   ├── /processed
│   │   ├── orthologous_proteins.csv
│   │   ├── paralogoues_proteins.csv
│   │   └── other_analyses
│   └── /results
│       ├── GO_analyses
│       ├── KEGG_analyses
│       └── SignalP_analyses
│
├── /scripts
│   ├── /orthofinder
│   │   └── orthofinder_script.sh
│   ├── /functional_analysis
│   │   ├── GO_script.sh
│   │   ├── KEGG_script.sh
│   │   └── SignalP_script.sh
│   └── /paralogoues_analysis
│       
│
├── /documentation
│   ├── README.md
│   ├── CONTRIBUTING.md
│   ├── LICENSE.md
│   └── /reports
│
│
├── /figures
|
│
├── .gitignore
│
└── README.md
```
