
# 🚜 Crop Price Prediction System

A smart **Crop Price Prediction System** that uses **Machine Learning** to predict prices of various crops based on **crop type**, **city**, **season**, and **temperature**. This project combines a trained **XGBoost** model, a **Flask API**, and a simple **HTML front-end** to provide real-time price predictions.

---

## 📁 Project Structure

1.app.py: The Flask application that serves the API and static files.<br>
2.index.html: The HTML file for the user interface, placed in the static directory.<br>
3.xgb_model.pkl: The trained XGBoost model saved as a pickle file.<br>
4.label_encoders.pkl: The label encoders for categorical features saved as a pickle file.<br>
5.scaler.pkl: The scaler for feature scaling saved as a pickle file.<br>

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
