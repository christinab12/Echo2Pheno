# Echo2Pheno

![stability-frozen](https://img.shields.io/badge/stability-locked-blue.svg)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/HelmholtzAI-Consultants-Munich/Echo2Pheno)

## What is this?
This repository provides the code for _Echo2Pheno: A deep learning application to uncover echocardiographic phenotypes_. Echo2Pheno consists of two modules:

*  Echo2Pheno Module I includes two neural networks, one for assessing the quality of acquisition of echocardiograms and the second for segmenting the Left Ventricle Inner Diameter traces. From a combination of these various heart features of the mouse in high quality of acquisition regions are extracted and can be used for Module II.
* Echo2Pheno Module II incorporates a statistical nonparametric hypothesis-testing module to investigate whether the mutant and control measurements of a study are drawn from the same statistical distribution.

![image](https://github.com/HelmholtzAI-Consultants-Munich/Echo2Pheno/blob/master/Echo2Pheno_graphical.png)


## Installation

The code has been tested with Python 3.7 and 3.9 environments. To install the necessary packages for Echo2Pheno run:

```
pip install -r requirements.txt
```

If you are using conda you may need to first install pip by: ```conda install pip```. 
