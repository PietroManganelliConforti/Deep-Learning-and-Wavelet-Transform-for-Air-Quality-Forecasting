# Deep Learning and Wavelet Transform for Air Quality Forecasting (ICIAP2023)

## Details

- Dataset: https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set


## Installation
`pip install -r requirements.txt`


## 2D dataset generation

`./generate_datasets.sh`


## Training and evaluation

- Baseline approach: `./run_train_1D.sh`

- Proposed method:

    - different input parameters combinations (table 1): `./run_train_2D_combos.sh`

    - different mother wavelets (table 2): `./run_train_2D_wavelets.sh`

