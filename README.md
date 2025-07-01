# Insurance Premium Prediction

A simple ML project to predict insurance premiums based on a person's health and demographic info.

## 📊 Dataset

[Insurance Premium Dataset on Kaggle](https://www.kaggle.com/noordeen/insurance-premium-prediction)

## ⚙️ Tech Stack

- Python
- CatBoost Regressor
- Flask
- DVC
- Pytest / Tox
- Docker

## 🚀 How to Run

```bash
git clone https://github.com/mohitrajrathor/insurance_premium_prediction_mlops.git
cd insurance_premium_prediction_mlops

conda create -p venv python=3.8 -y
conda activate venv

pip install -r requirements.txt
python app.py
```

## 🧪 Testing

```bash
pytest -v
tox -r
```

## 🛠 Project Structure

* `config.yaml`, `params.yaml` – config files
* `app.py` – main Flask app
* `main.py` – training pipeline entry point
* `src/` – code for training and prediction

## ✍️ Author

Email: [mohitrajrathor@gmail.com](mailto:mohitrajrathor@gmail.com)

---
