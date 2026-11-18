# 🩺 Breast Cancer Prediction System

A Machine Learning web application that predicts whether a breast tumor is **Malignant** or **Benign** using a trained Support Vector Classifier (SVC) model.

The application is built with Python and Streamlit, providing an interactive interface where users can enter tumor-related measurements and receive a model prediction.

## 📌 Project Overview

Breast cancer is a serious health condition where early clinical assessment is important. This project demonstrates how machine learning can be used to classify breast tumor measurements into two categories:

- **Malignant:** The model's malignant classification.
- **Benign:** The model's benign classification.

The project uses a pre-trained SVC model stored in a Joblib file and loads it into a Streamlit application.

## ✨ Features

- Machine learning-based prediction using SVC.
- Interactive Streamlit web interface.
- Input form with 30 numerical features.
- Three-column input layout.
- Loads a saved model using Joblib.
- Displays the prediction in the application.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical operations |
| Pandas | Data handling |
| Scikit-learn | Machine learning |
| Support Vector Classifier (SVC) | Classification model |
| Joblib | Model loading |
| Streamlit | Web application interface |

## 📂 Project Structure

```text
Breast_Cancer_Prediction/
│
├── app1.py
├── SVC.joblib
├── requirements.txt
├── runtime.txt
└── README.md
```

## 📊 Input Features

The application accepts 30 numerical measurements grouped into three categories.

### 1. Mean Features
- Radius Mean
- Texture Mean
- Perimeter Mean
- Area Mean
- Smoothness Mean
- Compactness Mean
- Concavity Mean
- Concave Points Mean
- Symmetry Mean
- Fractal Dimension Mean

### 2. Standard Error Features
- Radius SE
- Texture SE
- Perimeter SE
- Area SE
- Smoothness SE
- Compactness SE
- Concavity SE
- Concave Points SE
- Symmetry SE
- Fractal Dimension SE

### 3. Worst Features
- Radius Worst
- Texture Worst
- Perimeter Worst
- Area Worst
- Smoothness Worst
- Compactness Worst
- Concavity Worst
- Concave Points Worst
- Symmetry Worst
- Fractal Dimension Worst

## ⚙️ Installation and Setup

### Step 1: Clone the repository

```bash
git clone https://github.com/Shani-0001/Breast_Cancer_Prediction.git
```

### Step 2: Open the project folder

```bash
cd Breast_Cancer_Prediction
```

### Step 3: Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Run the application

```bash
python -m streamlit run app1.py
```

The Streamlit application will open in your browser.

## 🚀 How to Use

1. Open the application.
2. Enter the 30 numerical input measurements.
3. Click the **Predict** button.
4. View the classification displayed by the application.

## 🧠 Machine Learning Model

- **Algorithm:** Support Vector Classifier (SVC)
- **Model file:** `SVC.joblib`
- **Model loading:** Joblib
- **Prediction interface:** Streamlit

The application loads the pre-trained model and uses it to generate predictions from the entered feature values.

## 🔮 Future Improvements

- Add model evaluation metrics such as accuracy, precision, recall and F1-score.
- Improve input validation and error handling.
- Add prediction confidence information where supported by the model.
- Improve the user interface and visualization.
- Add a properly documented dataset and model-training pipeline.

## ⚠️ Disclaimer

This project is developed for educational and demonstration purposes only. It is not a medical diagnostic tool and must not be used to diagnose, treat, or make medical decisions. Always consult qualified healthcare professionals for medical advice.

## 👨‍💻 Author

Shani Yadav

GitHub: https://github.com/Shani-0001/Breast_Cancer_Prediction

---

⭐ If you find this project useful, consider giving the repository a star!
