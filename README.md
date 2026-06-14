# SKRIPSI PAPER

## Repository Structure 
```
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
```

## Trained Models
The repository provides trained models in the following formats:

- `model/svm_linearsvc_data_2_2.pkl` — SVM model saved as a single `.pkl` file
- `model/indobert_data_2_2/` — IndoBERT model saved as a folder containing model 
  tensors, tokenizer files, and `le_bundle.pkl` for label encoding

These files represent the final models used in the study.

The inference implementation can be found in the **Inferensi Model** section of 
`indobert_modeling.ipynb` and `svm_modeling.ipynb`.

## How to Run

### Requirements
- Google Colab
- For SVM: trained model file (`svm_linearsvc_data_2_2.pkl`)
- For IndoBERT: trained model folder (`indobert_data_2_2/`) containing model 
  tensors, tokenizer, and label encoder
- External test dataset

### Steps
1. Open `indobert_modeling.ipynb` or `svm_modeling.ipynb` in Google Colab.
2. Upload the external dataset to the Colab environment.
   - **SVM**: upload `svm_linearsvc_data_2_2.pkl`
   - **IndoBERT**: upload the entire `indobert_data_2_2/` folder
3. Update the model path variable in the **Inferensi Model** section:
   - **SVM**: update `MODEL_PATH` to the uploaded `.pkl` file path
   - **IndoBERT**: update `BUNDLE_PATH` to the uploaded folder path
4. Update the dataset path variable to match the uploaded dataset location.
5. Run only the cells under **Inferensi Model** section sequentially.

## Author
Elita Camellia

Dhiya Zhafirah

Kanisa Anjani Santoso
