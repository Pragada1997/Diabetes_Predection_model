# Diabetes Prediction Using Logistic Regression

## 📌 Project Overview

This project uses **Machine Learning and Logistic Regression** to predict whether a person is diabetic based on medical measurements. The model is built using Python and Scikit-learn and deployed as an interactive web application using **Streamlit**.

The application allows users to enter medical feature values and receive a diabetes prediction.

> **Disclaimer:** This project is intended for educational purposes only and should not be used as a substitute for professional medical advice or diagnosis.

## ✨ Features

- Exploratory Data Analysis (EDA)
- Data visualization and statistical analysis
- Data preprocessing and train-test splitting
- Logistic Regression classification model
- Model evaluation using accuracy
- Interactive Streamlit web application
- Real-time predictions based on user inputs

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Scikit-learn** – Machine Learning model development and evaluation
- **Streamlit** – Web application development

## 📂 Dataset

The project uses a diabetes dataset stored in `diabetes.csv`.

The dataset contains the following input features:

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose measurement |
| BloodPressure | Blood pressure measurement |
| SkinThickness | Skin thickness measurement |
| Insulin | Insulin measurement |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function value |
| Age | Age of the individual |
| Outcome | Target variable: 0 or 1 |

**Target variable:**
- `0` – Non-diabetic class
- `1` – Diabetic class

## ⚙️ Machine Learning Workflow

1. Load the diabetes dataset using Pandas.
2. Perform exploratory data analysis.
3. Analyze feature distributions and outcome counts.
4. Separate input features and the target variable.
5. Split the dataset into training and testing sets (80:20).
6. Train a Logistic Regression model using Scikit-learn.
7. Generate predictions on the test dataset.
8. Evaluate model performance using accuracy.
9. Integrate the model into a Streamlit application.
10. Deploy the application for interactive predictions.

## 📁 Project Structure

```text
Diabetes-Prediction/
│
├── diabetes_prediction.py
├── diabetes.csv
├── requirements.txt
└── README.md
```

- `diabetes_prediction.py` – Streamlit application and prediction logic
- `diabetes.csv` – Dataset used for training and prediction
- `requirements.txt` – Required Python libraries
- `README.md` – Project documentation

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone <gh repo clone Pragada1997/Diabetes_Predection_model>
cd Diabetes-Prediction
```

Replace the placeholder with your actual GitHub repository URL.

### 2. Install the required libraries

Create a `requirements.txt` file containing:

```text
streamlit
pandas
numpy
scikit-learn
matplotlib
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit application

```bash
streamlit run diabetes_prediction.py
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:8501
```

## 🖥️ How to Use

1. Launch the Streamlit application.
2. Enter the required medical feature values.
3. Click the prediction button.
4. View the predicted class displayed by the application.

## 📊 Model Evaluation

The model's performance is evaluated using **Accuracy Score** from Scikit-learn.

**Model:** Logistic Regression  
**Evaluation metric:** Accuracy

> Add your actual test accuracy after running the model. Do not report an estimated value as a measured result.

## 🔮 Future Improvements

- Evaluate the model using a confusion matrix, precision, recall, F1-score, and ROC-AUC.
- Improve data preprocessing and input validation.
- Compare Logistic Regression with other classification algorithms.
- Improve the Streamlit interface and visualization.
- Save and load the trained model for deployment.
- Deploy the application online using Streamlit Community Cloud.

## 👨‍💻 Author

**Ramesh Pragada**


---

⭐ If you find this project useful, consider starring the repository!
