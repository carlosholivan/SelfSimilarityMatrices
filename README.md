<img src="https://www.unizar.es/sites/default/files/identidadCorporativa/imagen/logoUZ.png"  width="480">

# MUSIC STRUCTURE ANALYSIS

## Introduction
Music Structure Analysis is a research part in Music Information Retrieval (MIR). Since 2009, MIREX's campaigns have been tested this algorithms which are composed by unsupervised and end-to-end methods which both of them take as inputs audio features such as MFCCs, chroma vectors or spectrograms, and the well-known self-similarity (lag) matrices.

In this repository, we show how these input matrices are obtained following previous works methods. The code has been programmed in the University of Zaragoza, in the Department of Electronic Engineering and Communications by Carlos Hernández, David Díaz-Guerra and José Ramón Beltrán.

## Repository Organization

The actual files in the repository are divided in:

### Jupyter Notebooks

| Notebook name | Description | Paper Title | Link to Paper | Paper Authors | Year | Journal/Conference |
| --- | --- | --- | --- | --- | --- | --- |
| SelfSimilarityLagMatrix-Grill_Schluter.ipynb | SSLM calculated from MFCCs and cosine distance | "Music Boundary Detection using Neural Networks on Spectrograms and Self-Similarity Lag Matrices" | http://www.ofai.at/~jan.schlueter/pubs/2015_eusipco.pdf | T. Grill and J. Schlüter | 2015 | EUPSICO |
| SelfSimilarityMatrix_Serra.ipynb | Recurrence plot and SSM calculated from MFCCs | "Unsupervised Music Structure Annotation by Time Series Structure Features and Segment Similarity" | https://ieeexplore.ieee.org/abstract/document/6763101/ | J. Serrà, M. Müller, P. Grosche, J. Ll. Arcos | 2014 | IEEE |


## Prerequisites

Python 3.5 or later. In Ubuntu, Mint and Debian Python 3 can be installed like this:

```
sudo apt-get install python3 python3-pip
```

Librosa 0.7.2 - https://librosa.github.io/librosa/install.html

```
sudo pip install librosa
```

If you use conda/Anaconda environments, librosa can be installed from the conda-forge channel:

```
conda install -c conda-forge librosa
```

## Webs of Interest

MIREX - https://www.music-ir.org/mirex/wiki/MIREX_HOME
MIR - https://musicinformationretrieval.com/

## Authors

* **Carlos Hernández** - carloshero@unizar.es
* **David Díaz-Guerra** - ddga@uniza.es
* **José Ramón Beltrán** - jrbelbla@unizar.es

