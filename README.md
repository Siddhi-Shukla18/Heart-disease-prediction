# Heart Disease Prediction

This project predicts the likelihood of heart disease in patients using a trained Random Forest model.  
It includes a web app interface for easy predictions.

## Project Overview
Heart disease is one of the leading causes of death worldwide.  
This app predicts the risk of heart disease based on patient health parameters.

## Files
- `app.py` : Main app file (Streamlit/Flask interface)  
- `HeartDPrediction.py` : Contains the ML model and prediction functions  
- `randomforest.pkl` : Trained Random Forest model  

## Technologies Used
- Python
- Streamlit
- Pandas, NumPy
- Scikit-learn

## How to Run
1. Clone the repository
2. Install required libraries:  
   ```bash
   pip install -r requirements.txt

## Run the app
```bash
streamlit run app.py
