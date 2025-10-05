# 🧠 Employee Attrition & Salary Forecasting – ML Pipeline

End-to-end notebooks for exploring, modeling, and predicting **employee attrition** and **future salaries**.  
Includes EDA → feature engineering → multiple models (incl. XGBoost) → predictions & reports.

## ✨ What’s inside
- `notebooks/MLphase*.ipynb` – phased workflow (EDA → models → evaluation)
- `data/raw/` – original dataset(s) (kept out of git if large)
- `data/processed/` – cleaned/feature-ready data
- `reports/predictions/` – saved CSV predictions/metrics
- `docs/` – images used in README

## 📦 Data
- Raw file(s): place in `data/raw/` (e.g., `employee_dataset.xlsx`)
- Processed: `data/processed/cleaned_employee_data.csv`
> Large data stays out of git; keep small samples only.

## 📊 Outputs
- Predictions & reports saved under `reports/predictions/`
- Add plots under `docs/` and embed them in this README

## 🧰 Tech
Python, Pandas, NumPy, scikit-learn, XGBoost, Matplotlib/Seaborn, Jupyter.  

## 🚀 Quickstart
```bash
python -m venv venv
# Windows
.\venv\Scripts\activate
# macOS/Linux: source venv/bin/activate
pip install -r requirements.txt
# Launch notebooks
jupyter notebook
