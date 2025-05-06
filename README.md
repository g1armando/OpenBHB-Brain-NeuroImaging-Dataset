# 🧠 Brain Age Prediction using the OpenBHB MRI Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)  
[![Python Version](https://img.shields.io/badge/python-3.8%2B-brightgreen)](#requirements)

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Models](#models)
- [Getting Started](#getting-started)
- [Citation](#citation)
- [License](#license)

## Overview
Descrizione del progetto...

## Dataset
Tutti i dati per il dataset **OpenBHB** sono stati scaricati da [IEEE DataPort](https://ieee-dataport.org/open-access/openbhb-multi-site-brain-mri-dataset-age-prediction-and-debiasing).

## Models
- **Classical ML**: Linear Regression, Random Forest, XGBoost (MAE ~4–4.5 anni)  
- **3D CNN** su volumi sMRI (in corso su A100 GPUs)

## Getting Started
1. `git clone ...`
2. `pip install -r requirements.txt`
3. `python train.py --config configs/full_dataset.yaml`

## Citation
> Dufumier, B., Grigis, A., Victor, J., Ambroise, C., Frouin, V., & Duchesnay, E. (2022).  
> *OpenBHB: a Large-Scale Multi-Site Brain MRI Data-set for Age Prediction and Debiasing*. **NeuroImage**.

## License
MIT © [Tuo Nome](https://github.com/tuo-username)
