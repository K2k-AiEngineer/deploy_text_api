# 🍽️ Vegan Ingredients Classifier API

Welcome to the **Vegan Ingredients Classifier API**! This API allows users to classify ingredients as vegan or non-vegan based on provided lists and machine learning models.

## 🏗️ Project Structure

```bash
Vegan-Ingredients-Classifier-API/
├── app.py                     # Main FastAPI application file
├── vegan.txt                  # File containing vegan ingredients
├── non-vegan.txt              # File containing non-vegan ingredients
├── tokenizer.pkl              # Pickle file for the tokenizer
├── count_vectorizer.pkl       # Pickle file for the count vectorizer
├── nb_model.pkl               # Pickle file for the Naive Bayes model
├── log_reg_model.pkl          # Pickle file for the Logistic Regression model
├── rf_model.pkl               # Pickle file for the Random Forest model
├── xgb_model.pkl              # Pickle file for the XGBoost model
├── lstm_model.h5              # TensorFlow model file for LSTM
├── bi_lstm_model.h5           # TensorFlow model file for Bi-LSTM
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
```

## ⚙️ Technology Stack

- **Backend Framework**: FastAPI
- **Machine Learning**: Scikit-learn, XGBoost, TensorFlow/Keras
- **Data Storage**: Python files for ingredient lists
- **Model Serialization**: Pickle for model storage
- **Deployment**: Render or AWS for live deployment
- **CORS Middleware**: FastAPI's built-in CORS middleware for cross-origin requests

## 🚀 Getting Started

### Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.7 or later
- pip (Python package installer)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Vegan-Ingredients-Classifier-API.git
   cd Vegan-Ingredients-Classifier-API

   Install the required packages
   pip install -r requirements.txt

## Running the API Locally
uvicorn app:app --reload


## 🧪 Testing the API
You can test the API by sending requests to the /classify endpoint. You can use tools like Postman or cURL to test the functionality.

## 📜 License
This project is licensed under the MIT License.

## 🔗 Render Testing URL
You can test the live API here: Vegan Classification API.
https://vegan-text-api.onrender.com/classify

   

   
