# Car Price Prediction

https://lh3.googleusercontent.com/pw/AP1GczN1AtwhM_9heJosIL3XstsLp2m4AKL7ZL0JVZozTmBEgtiLDfQ0Zn-2toU_f-uh_r9vOuxAgKI8r28XTm3uoPSF-hKi0XUaf2RSPTskd63LVIZTNho2gawryTShtzCsJnWaMrYI5La1y0Wy4LR6zATh=w798-h400-s-no-gm?authuser=0
## Overview
This project is a web-based application that predicts the selling price of a used car based on user inputs such as car company, model, year, fuel type, and kilometers driven. It is built using Flask for the backend and a trained Linear Regression model for predictions.

## Features
- Predicts car prices using machine learning.
- User-friendly web interface.
- Uses Flask as a backend framework.
- Deployed using Gunicorn for production.
- Styled with Bootstrap and custom CSS.

## Tech Stack
- **Backend**: Flask, Flask-Cors
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Machine Learning**: Scikit-learn, Pandas, NumPy

## Installation & Setup
### 1. Clone the repository
```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
python app.py
```
The application will be available at `http://127.0.0.1:5000/`.

## File Structure
```
|-- app.py                # Flask application
|-- LinearRegressionModel.pkl  # Trained ML model
|-- Cleaned_Car_data.csv  # Dataset used for training
|-- templates/
|   |-- index.html        # Frontend UI
|-- static/
|   |-- css/
|   |   |-- style.css     # Custom CSS
|-- requirements.txt      # Python dependencies
|-- README.md             # Project documentation
```

## Usage
1. Open the application in your browser.
2. Select car company, model, year, fuel type, and enter kilometers driven.
3. Click "Predict Price" to get the estimated car price.

## Contributing
Feel free to contribute by forking the repository and creating pull requests.

## License
This project is licensed under the MIT License.

