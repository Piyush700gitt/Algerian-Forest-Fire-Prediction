# 🔥 Algerian Forest Fire Prediction

A Machine Learning web application that predicts the **Fire Weather Index (FWI)** using the Algerian Forest Fires dataset. The project includes Exploratory Data Analysis (EDA), Feature Engineering, Model Training, and deployment using Flask.

---

## 📌 Project Overview

This project predicts the **Fire Weather Index (FWI)** based on weather and environmental conditions using a trained **Ridge Regression** model.

The workflow includes:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Serialization using Pickle
- Flask Web Application for Prediction

---

## 🚀 Features

- Predict Fire Weather Index (FWI)
- User-friendly Flask web interface
- Ridge Regression model
- StandardScaler preprocessing
- Trained model loaded using Pickle

---

## 📊 Dataset

The project uses the **Algerian Forest Fires Dataset** containing meteorological and fire-related attributes.

### Input Features

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC
- DMC
- ISI
- Classes
- Region

### Output

- Fire Weather Index (FWI)

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Pickle
- HTML

---

## 📂 Project Structure

```text
Algerian-Forest-Fire-Prediction
│
├── models/
│   ├── ridge.pkl
│   ├── scaler.pkl
│   └── Algerian_forest_fires_dataset_UPDATE.csv
│
├── notebooks/
│   ├── 2.0-EDA And FE Algerian Forest Fires.ipynb
│   └── 3.0-Model Training.ipynb
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── application.py
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/Piyush700gitt/Algerian-Forest-Fire-Prediction.git
```

Move into the project directory

```bash
cd Algerian-Forest-Fire-Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python application.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 🤖 Machine Learning Model

- Ridge Regression
- StandardScaler for feature scaling

---

## 📸 Application Preview

(Add a screenshot of your Flask application here.)

---

## 📈 Future Improvements

- Improve the UI using Bootstrap
- Deploy on Render
- Add model evaluation metrics on the web page
- Add input validation

---

## 👨‍💻 Author

**Piyush Shrivastava**

GitHub: https://github.com/Piyush700gitt
