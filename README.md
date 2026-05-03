# Heart Stroke Prediction App

A Machine Learning web application built using Streamlit and Scikit-learn to predict the risk of heart stroke based on health-related input parameters.

## Features

- Predict heart stroke risk in real time
- User-friendly web interface using Streamlit
- Trained KNN (K-Nearest Neighbors) model
- Data preprocessing with StandardScaler
- Fast and interactive predictions

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Project Structure

```bash
├── app.py
├── KNN_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
├── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/heart-stroke-predictor.git
cd heart-stroke-predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Model Used

K-Nearest Neighbors (KNN)

The model is trained on heart health-related data and predicts the possibility of heart stroke based on user inputs.

## Deployment

This application is deployed using Streamlit Community Cloud.

## Future Improvements

- Improve model accuracy
- Add more ML models for comparison
- Better UI/UX enhancements
- Deploy API version

## Author

Harshit Madnani
