# ❤️ Heart Disease Prediction using Machine Learning

## Objective

This project predicts whether a person is likely to have heart disease using a **Logistic Regression** model. The trained model is deployed as a **Flask web application**.

---

## Dataset

- Dataset: Heart Disease Prediction Dataset
- Total Records: 1025
- Features: 13
- Target Variable:
  - 0 = No Heart Disease
  - 1 = Heart Disease

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- Joblib
- HTML/CSS
- GitHub
- Render

---

## Machine Learning Model

- Algorithm: Logistic Regression
- Train-Test Split: 80:20
- Accuracy: **79.51%**

---

## Project Structure

```text
HeartDiseaseDeployment/
├── app.py
├── model.pkl
├── requirements.txt
├── README.md
├── train_model.py
├── heart.csv
├── templates/
     └── index.html
```

---

## Deployment

The Flask application has been successfully deployed on **Render**.

### Live Application

https://heartdiseasedeployment-tkqe.onrender.com/

### How to Test the Application

1. Open the deployed application using the above URL.
2. Enter valid patient details in all the input fields.
3. Click the **Predict** button.
4. The application will display one of the following results:
   - **Heart Disease Detected**
   - **No Heart Disease**

---

## How to Run

### 1. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the Flask application

```bash
python app.py
```

### 3. Open your browser

```
http://127.0.0.1:5000/
```

---

## Future Improvements

- Improve model accuracy using ensemble learning methods such as Random Forest or XGBoost.
- Enhance the user interface.
- Add input validation and error handling.
- Containerize the application using Docker.
- Deploy with CI/CD for automated updates.

---

## Conclusion

This project demonstrates the complete end-to-end deployment of a machine learning model for heart disease prediction. The Logistic Regression model achieved an accuracy of **79.51%** and was successfully integrated into a Flask web application. During deployment, configuring the project structure and ensuring all required files were correctly uploaded to GitHub and Render were important steps. This assignment highlights the importance of MLOps practices such as model serialization, version control, cloud deployment, and serving predictions through a web application, making machine learning solutions accessible to end users.

---

## Author

**Satyam Swaraj**

B.Tech Computer Science and Engineering

VIT Bhopal University
