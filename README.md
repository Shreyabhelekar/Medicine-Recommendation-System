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

1. Clone the Repository
   git clone https://github.com/Shreyabhelekar/medicine-recommendation-system.git
   cd medicine-recommendation-system

2. Install Dependencies
    pip install -r requirements.txt

3. Ensure Directory Structure
.
|── app.py
├── models/
│   └── svc.pkl
├── datasets/
│   ├── symtoms_df.csv
│   ├── description.csv
│   ├── precautions_df.csv
│   ├── medications.csv
│   └── diets.csv
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   └── blog.html


4. Run the App
   python app.py

Then visit http://127.0.0.1:5000 in your browser.






