# Bangalore House Price Predictor

## Overview
The Bangalore House Price Predictor is a web application built using Python and Flask. It allows users to input details such as the location in Bangalore, the number of bedrooms, bathrooms, and the square footage area of a property to get an estimated price. The app uses a regression model trained on real estate data to provide accurate predictions.

## Features
- **Location-Based Predictions**: Accepts Bangalore locations for accurate price estimation.
- **User Inputs**: Allows users to input:
  - Number of bedrooms (BHK)
  - Number of bathrooms
  - Total square footage area
- **Machine Learning**: Utilizes a regression model for price prediction.
- **Frontend Integration**: Interactive user interface built with HTML and CSS.

## Tech Stack
### Backend:
- Python
- Flask
- scikit-learn
- pandas
- numpy
- pickle (for model serialization)

### Frontend:
- HTML
- CSS

## How It Works
1. **Data Input**: The user provides inputs through the web interface.
2. **Model Prediction**: The inputs are passed to a trained regression model, which computes the estimated price.
3. **Output Display**: The predicted price is displayed on the web page.

## Installation

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/PrateekPsingh/House_Prediction_Banglore.git
   cd bangalore-house-predictor
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask application:
   ```bash
   python app.py
   ```
4. Open the app in your browser:
   ```
   http://127.0.0.1:5000/
   ```

## Model Training
1. **Dataset**: The regression model is trained using real estate data from Bangalore.
2. **Libraries Used**:
   - scikit-learn for model building
   - pandas for data manipulation
   - numpy for numerical computations
3. **Serialization**: The trained model is saved using pickle for later use in the application.


## Usage
1. Open the application in your browser.
2. Enter the required details:
   - Location in Bangalore
   - Number of bedrooms (BHK)
   - Number of bathrooms
   - Square footage area
3. Click the **Predict** button to view the estimated price.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [scikit-learn](https://scikit-learn.org/)
- [Flask](https://flask.palletsprojects.com/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)

