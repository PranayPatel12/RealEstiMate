# RealEstiMate

🏡 House Price Prediction Web App
A machine learning-powered web application built using FastAPI that predicts the price of a house based on user-input features like size, number of bedrooms, location coordinates, and more.


🔧 Tech Stack
Programming langugage: Python

Frontend: HTML, CSS (Jinja2 templates)

Backend: FastAPI

Machine Learning: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (Random Forest, Linear Regression, etc.)

Model Serialization: joblib


📦 Features
Predict house prices in real-time

Multiple regression models trained and evaluated

Interactive and user-friendly web form

Styled UI for better user experience


🚀 How to Run:

1. Install dependencies:
   Run the following command to install the necessary packages listed in your requirements.txt file:
     pip install -r requirements.txt
2. Start the app:
   Option 1: Use uvicorn to start the FastAPI app with the --reload option (for auto-reloading on code changes):
     python -m uvicorn main:app --reload
   Option 2: Alternatively, you can run the main.py file directly if it's set up as an entry point:
     python main.py
3. Visit the app:
   Open your browser and go to:
     http://127.0.0.1:8000
This gives you the flexibility to run the app either through uvicorn or by executing the main.py script directly.


📁 Project Structure
house_price_app/
│
├── main.py                    # FastAPI application
├── house_price_model.pkl      # Trained ML model
├── requirements.txt           # Dependencies
├── templates/
│   └── form.html              # HTML form for user input
└── HousePricePrediction.ipynb # Model training & evaluation notebook


🧠 Model Info
Multiple regression models were trained and evaluated using features such as:

BHK details

Square footage

Latitude & Longitude

Construction status

Ownership & resale details

The best-performing model was saved and integrated into the API for predictions.
