# 🔥 Workforce Burnout Prediction System — Streamlit App

## Project
Workforce Burnout Prediction, Sick-Day Forecasting & HR Intervention Recommendation System  
**Dataset:** IBM HR Analytics Employee Attrition & Performance  
**Team:** Faith Ngendo, Alan Muchiri, William Nyawir, Sarah Owendi, Anthony Njeru

---

## Quick Start

```bash
# 1. Clone / navigate to project folder
cd burnout_app

# 2. Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run app.py
```

Then open http://localhost:8501 in your browser.  
Upload `WA_Fn-UseC_-HR-Employee-Attrition.csv` in the sidebar.

---

## App Structure

| Tab | Content |
|-----|---------|
| 📊 Overview & EDA | Class distribution, OT charts, heatmap |
| 🎯 Stage 1 — Classification | LR vs RF metrics, confusion matrices, feature importance |
| 📅 Stage 2 — Sick-Day Forecast | Linear/RF/XGBoost regression, actual vs predicted, residuals |
| 💡 Stage 3 — HR Interventions | Priority distribution, sample recommendations, CSV export |
| 🔍 Employee Lookup | Per-employee risk profile + interventions |

---

## Deploy to Streamlit Community Cloud (Free)

1. Push this folder to a GitHub repo
2. Go to https://share.streamlit.io → **New app**
3. Select your repo, branch `main`, file `app.py`
4. Click **Deploy** — live URL in ~2 minutes

> The dataset is uploaded at runtime via the sidebar uploader, so no CSV needs to be committed.

---

## Project Structure

```
burnout_app/
├── app.py            ← Main Streamlit app
├── requirements.txt  ← Python dependencies
└── README.md         ← This file
```
