# Bengaluru House Price Prediction

## Project Overview

This project builds a real estate price prediction website for Bengaluru using machine learning. It follows a step-by-step process:

Model Development: Trains a Linear Regression model on Bengaluru home price data from Kaggle.

Backend Development: Uses Python Flask to serve HTTP requests with the trained model.

Frontend Development: An interactive website built with HTML, CSS, and JavaScript.


## Technologies Used
- Python for backend development and machine learning
- Flask for API server
- NumPy & Pandas for data processing
- Matplotlib for data visualization
- Scikit-learn for model training
- Jupyter Notebook for experimentation
- HTML/CSS/JavaScript for UI

## Project Structure
```
BHP/
│── client/                 # Frontend (HTML, CSS, JS)
│── model/                  # Machine learning model files
│── server/                 # Backend API using Flask
│   │── artifacts/          # Saved model & column metadata
│   │── util/               # Utility functions
│   └── app.py              # Flask API entry point
│── bengaluru_house_prices.csv  # Dataset
│── README.md               # Project documentation
```

## How to Run Locally
### 1. Clone the Repository
```
git clone https://github.com/your-username/BHP.git
cd BHP
```
### 2. Set Up a Virtual Environment (Optional but Recommended)
```
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```
### 3. Install Dependencies
```
pip install -r server/requirements.txt
```
### 4. Run the Flask Server
```
python server/app.py
```
The server will start at http://127.0.0.1:5000.
### 5. Run the Frontend
- Open client/index.html in your browser.
- Enter details (sqft, BHK, bath, location) and get predicted prices!

## Features
1. Predicts house prices based on input parameters
2. Supports multiple locations in Bengaluru
3. Clean and interactive UI for easy predictions
4. API-based architecture for scalability

## License
This project is open-source under the MIT License.

