# Brain Age Prediction with OpenBHB MRI Dataset

This repository contains the code and experiments for predicting **brain age** using the **OpenBHB** dataset—a large-scale, multi-site collection of structural brain MRI scans and associated biological measurements.

## Overview
- **Goal**: Estimate a person’s brain age (appearance-based) from MRI data.
- **Applications**: Early detection of neurodegenerative diseases (e.g., Alzheimer’s).

## Dataset
All data were downloaded from [IEEE DataPort](https://ieee-dataport.org/open-access/openbhb-multi-site-brain-mri-dataset-age-prediction-and-debiasing). The dataset includes scans from ~4,000 subjects across 10 sites (60–70 GB total).

## Installation
```bash
git clone https://github.com/g1armando/OpenBHB-Brain-NeuroImaging-Dataset.git
cd OpenBHB-Brain-NeuroImaging-Dataset
# to activate your environment:
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Citation
> Dufumier, B., Grigis, A., Victor, J., Ambroise, C., Frouin, V., & Duchesnay, E. (2022).  
> *OpenBHB: a Large-Scale Multi-Site Brain MRI Data-set for Age Prediction and Debiasing*. **NeuroImage**.

## License
This project is licensed under MIT. See [LICENSE](LICENSE) for details.
