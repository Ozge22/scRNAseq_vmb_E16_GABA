# sc_RNA_seq_ventralmidbrain_E16

Version 0

single cell l sequencing of mouse ventral midbrain GABAergic neurons at E16

Language: Python 
Tested on MacOS version 10.15.2 (19C57)

Installation

Anaconda

If you do not have a working installation of Python 3.6 (or later), consider installing Miniconda (see Installing Miniconda). Then run:
conda install -c bioconda scanpy

Install the Leiden clustering package [Traag18] (improved Louvain clustering) via:
conda install -c conda-forge leidenalg

## Packages 

scanpy==1.4.5.dev180+g5d6f276 anndata==0.6.22.post1 umap==0.3.10 numpy==1.17.2 scipy==1.3.1 pandas==0.25.1 scikit-learn==0.21.3 statsmodels==0.10.1 python-igraph==0.7.1 louvain==0.6.1



## Project organization

```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── bin                <- Compiled and external code, ignored by git (PG)
│   └── external       <- Any external source code, ignored by git (RO)
├── config             <- Configuration files (HW)
├── data               <- All project data, ignored by git
│   ├── processed      <- The final, canonical data sets for modeling. (PG)
│   ├── raw            <- The original, immutable data dump. (RO)
│   └── temp           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── src                <- Source code for this project (HW)

```


## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## Citation

Please [cite this project as described here](/CITATION.md).
