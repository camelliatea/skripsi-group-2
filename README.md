# SKRIPSI PAPER

## Repository Structure 
skripsi-group-2/
├── dataset/
│   ├── final dataset internal
│   ├── final dataset external
├── model/
│   ├── indobert
│   ├── svm
├── notebook/
│   ├── EDA dataset internal
│   ├── EDA dataset external
│   ├── indobert modeling
│   ├── Kappa Test
│   ├── McNemar Test
│   ├── preprocessing data internal
│   ├── preprocessing data external
│   ├── svm modeling
└── README.md

## Trained Models

The repository provides trained models in `.pkl` format:

- model/svm_linearsvc_data_2_2.pkl
- model/indobert_data_2_2/le_bundle.pkl

These files represent the final models used in the study. 

The inference implementation can be found in the **Inferensi Model** section of `indobert_modeling.ipynb` and `svm_modeling.ipynb`, which demonstrates how the trained models are loaded and used to generate predictions on the external evaluation dataset.

## How to Run

### Requirements
- Google Colab
- Trained model file (`.pkl`)
- External test dataset

### Steps
1. Open `indobert_modeling.ipynb` or `svm_modeling.ipynb`.
2. Upload the trained model and external dataset.
3. Update `BUNDLE_PATH` and dataset path variables in **Inferensi Model** section.
4. Run the cells under **Inferensi Model** section only.

## Author
Elita Camellia

Dhiya Zhafirah

Kanisa Anjani Santoso
