<h2>Overview</h2><br>
This project is a crop price prediction system that uses machine learning models to predict the price of various crops based on input parameters such as crop type, city, season, and temperature. The system includes a trained model, a Flask API for predictions, and a simple HTML front-end for user interaction.

Project Structure
app.py: The Flask application that serves the API and static files.
index.html: The HTML file for the user interface, placed in the static directory.
xgb_model.pkl: The trained XGBoost model saved as a pickle file.
label_encoders.pkl: The label encoders for categorical features saved as a pickle file.
scaler.pkl: The scaler for feature scaling saved as a pickle file.
