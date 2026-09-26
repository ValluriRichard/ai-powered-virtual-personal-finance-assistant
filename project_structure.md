# Project Structure

```text
ai-powered-virtual-personal-finance-assistant/
├── AI_Powered_Virtual_Personal_Finance_Assistant.ipynb  # Main Colab/Jupyter notebook
├── README.md                                            # Project overview and setup
├── requirements.txt                                     # Python dependencies
├── .gitignore                                            # Files not to commit
├── LICENSE                                               # MIT license
├── project_structure.md                                  # Repository map
└── data/
    └── README.md                                         # Data-source / storage note
```

## Notebook flow

1. Environment setup
2. Dataset ingestion
3. Text preprocessing
4. Tabular preprocessing, anomaly labeling and SMOTE
5. Fraud/anomaly model benchmarking
6. Expense categorization benchmarking
7. Banking intent baseline benchmarking
8. DistilBERT fine-tuning
9. DistilBERT dynamic quantization
