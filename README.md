
# Drug Advisor Using Machine Learning


## Overview
This web application, built using Flask, provides drug recommendations based on patient symptoms. It uses machine learning models trained on a dataset of patient records to predict diseases and suggest appropriate medications, precautions, diets, and workouts.

## Features
- **Symptom Input:** Users can input symptoms via a web form.
- **Prediction:** Predicts the disease based on the symptoms using a trained Support Vector Machine (SVM) model.
- **Information Retrieval:** Provides disease descriptions, precautions, medications, recommended diets, and workout plans.
- **Web Pages:** Includes additional pages such as About, Contact, Developer, and Blog.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drug-advisor.git
   cd drug-advisor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

4. Open your web browser and navigate to `http://localhost:5000` to use the Drug Advisor web application.


## Technologies Used
- Python
- Flask
- HTML
- CSS
- Pandas
- Scikit-learn

## Files Structure
```
├── app.py
├── requirements.txt
├── datasets/
│   ├── symtoms_df.csv
│   ├── precautions_df.csv
│   ├── workout_df.csv
│   ├── description.csv
│   ├── medications.csv
│   └── diets.csv
└── models/
    └── svc.pkl
```

## Usage
1. Launch the Flask application:
   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://localhost:5000`.

3. Enter symptoms in the provided form and click on the Predict button to get recommendations.

