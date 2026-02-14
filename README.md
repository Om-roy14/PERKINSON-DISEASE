
directory structure

# parkinsons-voice-ai/
# │
# ├── README.md
# ├── requirements.txt
# ├── .gitignore
# │
# ├── data/
# │   ├── raw/
# │   │   ├── healthy/
# │   │   └── parkinson/
# │   │
# │   ├── processed/
# │   │   └── features.csv
# │   │
# │   └── interim/
# │
# ├── notebooks/
# │   ├── 01_data_exploration.ipynb
# │   ├── 02_feature_extraction_testing.ipynb
# │   ├── 03_model_training.ipynb
# │   └── 04_evaluation.ipynb
# │
# ├── src/
# │   ├── __init__.py
# │   │
# │   ├── feature_extraction.py
# │   ├── dataset_builder.py
# │   ├── preprocessing.py
# │   ├── train.py
# │   ├── evaluate.py
# │   └── utils.py
# │
# ├── models/
# │   ├── scaler.pkl
# │   ├── svm_model.pkl
# │   └── xgboost_model.pkl
# │
# ├── results/
# │   ├── plots/
# │   │   ├── roc_curve.png
# │   │   └── feature_importance.png
# │   │
# │   └── reports/
# │       └── evaluation_summary.txt
# │
# └── app/   (for future deployment phase)
#     └── app.py
