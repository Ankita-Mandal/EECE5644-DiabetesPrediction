# Diabetes Prediction — EECE 5644 Project

Binary classification of diabetes status on the CDC BRFSS 2015 survey.

## How to run `Diabetes_prediction_model.ipynb`

### 1. Clone the repo

```bash
git clone https://github.com/Ankita-Mandal/EECE5644-Diabetes_Prediction.git
cd EECE5644-Diabetes_Prediction
```

### 2. Create and activate a Python 3.10 virtual environment

**Windows (PowerShell):**
```powershell
python -m venv venv
venv\Scripts\Activate.ps1
```

**macOS / Linux:**
```bash
python3.10 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not present, install the packages used by the notebook directly:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost jupyter
```

### 4. Download the dataset

Download `diabetes_binary_health_indicators_BRFSS2015.csv` from
[Kaggle — Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
and place it in the `data/` folder:

```
diabetes-repo/
├── data/
│   └── diabetes_binary_health_indicators_BRFSS2015.csv
└── Diabetes_prediction_model.ipynb
```

### 5. Launch Jupyter and run the notebook

```bash
jupyter notebook Diabetes_prediction_model.ipynb
```

Run all cells in order (`Cell → Run All`).