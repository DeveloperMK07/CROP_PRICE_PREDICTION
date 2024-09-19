<h2>Overview</h2><br>
This project is a crop price prediction system that uses machine learning models to predict the price of various crops based on input parameters such as crop type, city, season, and temperature. The system includes a trained model, a Flask API for predictions, and a simple HTML front-end for user interaction.

<h3>Project Structure</h3><br>
app.py: The Flask application that serves the API and static files.<br>
index.html: The HTML file for the user interface, placed in the static directory.<br>
xgb_model.pkl: The trained XGBoost model saved as a pickle file.<br>
label_encoders.pkl: The label encoders for categorical features saved as a pickle file.<br>
scaler.pkl: The scaler for feature scaling saved as a pickle file.<br>

<h3>Usage</h3><br>
<h5>Access the Application</h5><br>
Open your web browser and navigate to http://127.0.0.1:5000. You should see the HTML form where you can input the crop type, city, season, and temperature.<br>
<h5>Submit the Form</h5><br>
Enter the required information and submit the form. The predicted price will be displayed based on the input parameters.<br>

<h3>License</h3><br>
This project is licensed under the MIT License - see the LICENSE file for details.<br>

<h3>Acknowledgments</h3><br>
XGBoost<br>
Flask<br>
scikit-learn<br>
