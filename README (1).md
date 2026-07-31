# Heart Disease Prediction using Machine Learning

## Objective
This project predicts whether a person is likely to have heart disease using a Logistic Regression model. The trained model is deployed as a Flask web application.

## Dataset
- Heart Disease Dataset
- Total Records: 1025
- Features: 13
- Target: Heart Disease (0 = No, 1 = Yes)

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

## Machine Learning Model
- Algorithm: Logistic Regression
- Train-Test Split: 80:20
- Accuracy: 79.51%

## Project Structure

HeartDiseaseDeployment/
│── app.py
│── train_model.py
│── model.pkl
│── heart.csv
│── requirements.txt
│── README.md
│── templates/
│     └── index.html

## How to Run

1. Install dependencies

pip install -r requirements.txt

2. Run the application

python app.py

3. Open your browser

http://127.0.0.1:5000/

## Future Improvements

- Use Random Forest or XGBoost
- Improve model accuracy
- Better user interface
- Deploy with Docker

## Conclusion

A Heart Disease Prediction model was successfully developed using Logistic Regression and deployed as a Flask application. The model achieved an accuracy of 79.51% and demonstrates a complete end-to-end machine learning deployment workflow.
