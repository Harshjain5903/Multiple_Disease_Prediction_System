# Multiple Disease Prediction — Harsh Jain

A beginner-friendly Streamlit web app that predicts **Diabetes**, **Heart Disease**, and **Parkinson’s** from simple inputs using pre-trained **scikit-learn** models.  
Built and personalized by **Harsh Jain**.

**Live app:** _add your Streamlit Cloud link here_  
**Code:** _this repo_  
**Tech:** Python 3.9 • Streamlit • scikit-learn • pickle

---

## ✨ Features
- Clean sidebar navigation and pages for 3 predictions (Diabetes, Heart, Parkinson’s). :contentReference[oaicite:0]{index=0}
- Loads pre-trained models from `.sav` files for instant predictions. :contentReference[oaicite:1]{index=1}
- Simple UI inputs; one-click “Test Result” buttons with success banners. :contentReference[oaicite:2]{index=2}

---

## 📦 Project structure
.
├── app.py
├── diabetes_model.sav
├── heart_disease_model.sav
├── parkinsons_model.sav
├── requirements.txt
├── runtime.txt
└── setup.sh

yaml
Copy code
- `app.py`: Streamlit app (UI + prediction logic). :contentReference[oaicite:3]{index=3}  
- `requirements.txt`: pinned deps used originally. :contentReference[oaicite:4]{index=4}  
- `setup.sh`: headless Streamlit config for deployment providers that need it. :contentReference[oaicite:5]{index=5}

---

## 🧰 Local setup (Mac / Linux / Windows)

> **Use Python 3.9** for smooth installs with the original dependencies.

```bash
# 1) Clone and enter
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# 2) Create & activate a virtual env (Python 3.9)
python3.9 -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# 3) Install dependencies
pip install --upgrade pip
pip install -r requirements.txt

# 4) Run the app
python -m streamlit run app.py
# Open the printed URL, e.g. http://localhost:8501
