# Medicine-Recommendation-System
This is a Flask-based web application that predicts possible diseases based on user-input symptoms and provides information like disease description, medications, precautions, and dietary recommendations. The backend is powered by a machine learning model trained on medical data.

# Features
- Predicts a disease based on symptoms

- Displays:

  1.Disease Description

  2.Medications

  3.Precautions

  4.Recommended Diet

- Simple and clean web interface

- Routes for Home, About, Contact, and Blog pages

# Machine Learning Model
Model Used: Support Vector Classifier (SVC)

Trained On: Medical dataset with symptoms and diseases

Serialized With: pickle

# Dataset Files
The following datasets are required and should be placed inside a datasets/ folder:

symtoms_df.csv – Mapping of symptom names

description.csv – Description of diseases

precautions_df.csv – Precautionary measures for diseases

medications.csv – Medications linked to diseases

diets.csv – Recommended diets for each disease

# Required Libraries:

Flask

NumPy

Pandas

scikit-learn

# Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/disease-prediction-flask.git
cd disease-prediction-flask
```

# Setup Instructions

1. Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install Dependencies

```bash
pip install -r requirements.txt
```

3. Run the Flask App

```bash
python app.py
```
The app will be available at: http://127.0.0.1:5000





