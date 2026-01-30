# House Price Predictor

This project predicts house prices based on user inputs such as location, area, number of bedrooms, and other features. The user enters their requirements through a Streamlit interface, and the model returns an estimated price. The system is built using Python and uses a trained machine learning model with MySQL for data handling.

## Technologies Used
- Python
- MySQL
- Machine Learning (Regression)
- Pandas, NumPy, Scikit-learn
- Streamlit

## Files in This Project
- app1.py: Main application file
- encoder.pkl: Saved encoder for categorical features
- house_price_prediction.pkl: Trained machine learning model
- HousePricePrediction.ipynb: Model training notebook
- HPP.ipynb: Additional experimentation notebook
- train.csv: Dataset used for training

## How to Run
1. Clone the repository:
   git clone https://github.com/krithik-vasu/House-Price-Predictor.git

2. Install the required libraries:
   pip install pandas numpy scikit-learn mysql-connector-python streamlit

3. Run the Streamlit app:
   streamlit run app1.py

## Output
The app displays a predicted house price based on the values entered by the user through the interface.
