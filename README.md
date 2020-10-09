Overview
========
This repository is used to re-create the plots and code for the PyData Global 2020 presentation.

Setup
=====
This code base utilizes anaconda for environmental dependencies. You may obtain anaconda [here](https://www.anaconda.com/distribution/).

Checkout the repository:

```
git clone https://github.com/matrix-profile-foundation/pydata2020.git pydata2020-mpf
```

Install dependencies:

```
cd pydata2020-mpf
conda env create -f environment.yaml 
conda activate pydata2020-mpf

# for a jupyter kernel with the conda environment
python -m ipykernel install --user --name=pydata2020-mpf
```

Code Execution
==============
The code is distributed using Jupyter notebooks. You may launch jupyter lab and view the notebooks with the following commands (assuming you are still in the local repository directory).

```
jupyter lab
```

Order of Review
===============
It is suggested, not required, to review the notebooks in the following order:

1. Dataset Overview
2. Transform Dataset
3. Computing Distance Matrix
4. MPDist vs Euclidean
5. MPDist vs DTW
6. Hierarchical Clustering
7. HDBScan Clustering
