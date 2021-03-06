# genereg

[![Documentation Status](https://readthedocs.org/projects/genereg/badge/?version=latest)](https://genereg.readthedocs.io/en/latest/?badge=latest)
[![PyPI version](https://img.shields.io/badge/pypi%20package-0.1.1-brightgreen.svg)](https://pypi.org/project/genereg/)
[![PyPI - Python Version](https://img.shields.io/badge/python-3.6-blue.svg)](https://github.com/Kia23/genereg)


This library implements a method for analyzing the regulation systems of target genes in a specific genetic pathology, such as a cancer. Adopting a linear regression approach, it builds a predictive model for the regulation of target genes expression, in order to identify the relevant features that explain the regulation of each gene of interest within patients affected by the pathology under analysis.
The regulation system of each target gene is analyzed singularly and independently, by assessing the effect of multiple regulatory factors on its expression, such as its methylation, the expression of other genes or the effect of transcription factors.

The full documentation can be found at the following link: https://genereg.readthedocs.io

We specifically applied our method to Ovarian Serous Cystadenocarcinoma, to investigate the regulatory system of 377 target genes belonging to 3 genomic pathways (DNA_REPAIR, STEM_CELLS, GLUCOSE_METABOLISM) relevant for this type of OV cancer. 
Results are graphically represented through expression networks, grouping target genes in subclasses according to their function inside their pathway. The complete networks file is available in the "OV Cancer Results" folder with its original Cytoscape format.