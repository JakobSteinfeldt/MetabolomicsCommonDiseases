<div align="center">

⛑ **Metabolomic profiles predict individual multi-disease outcomes** ⛑

[comment]: <> (<!--)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thbuerg/MetabolomicsCommonDiseases/blob/main/analysis/examples/MetabolomicsInference.ipynb)
[![Paper](https://img.shields.io/badge/Paper-Nature%20Medicine-red)](https://www.nature.com/articles/s41591-022-01980-3)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6200202.svg)](https://doi.org/10.5281/zenodo.6200202)
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[comment]: <> (-->)

</div>

## Description   
Here we present the downstream analysis for the paper "Metabolomic profiles predict individual multi-disease outcomes". Detailed instructions on the data preprocessing, model training and inference on new NMR data can be found [here](https://github.com/thbuerg/MetabolomicsCommonDiseases).

We provide a ready-to-use [Google colab notebook](https://colab.research.google.com/github/thbuerg/MetabolomicsCommonDiseases/blob/main/analysis/examples/MetabolomicsInference.ipynb) with a trained version of our MetabolomicStateModel. Upload your dataset of Nightingale NMR metabolomics and run the model!
**NOTE**: Data must be provided in [this format](https://github.com/thbuerg/MetabolomicsCommonDiseases/blob/main/analysis/examples/sample.csv).

## Content
This repository contains code to aggregate and process metabolomics states (1_preparation) and reproduce the analyses (2_analyses) in the [UK Biobank](https://www.ukbiobank.ac.uk/).

- Aggregating the metabolomic states from models on the 22 independent recruitment centres of the UK Biobank.
- Standardizing and evaluating the metabolomic states by fitting linear COX Proportional Hazard models.
- Analyzing the discriminative performance and potential clinical utility with decision curves.
- Reproducing the visualization and analyses presented in this paper. 

## Citation   
```
@article{thisonecoolstory,
  title={Metabolomic profiles predict individual multi-disease outcomes},
  author={Thore Buergel, Jakob Steinfeldt},
  journal={tbd},
  year={2022}
}
```  

