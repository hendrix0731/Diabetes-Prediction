# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Overview
This project predicts diabetes using the **PIMA Diabetes Dataset** and a **Support Vector Machine (SVM) Classifier**. It processes patient health data, standardizes features, and classifies individuals as diabetic or non-diabetic.

---

## 🚀 Features
- Loads and preprocesses the dataset 📊
- Standardizes feature values for better accuracy ⚙️
- Splits data into **training** and **testing** sets 🎯
- Trains an **SVM classifier** for diabetes prediction 🤖
- Evaluates the model's accuracy 📈
- Accepts user input for real-time predictions 📝

---

## 📂 Dataset
The project uses the **PIMA Indian Diabetes Dataset**, which consists of:
- **Pregnancies**
- **Glucose level**
- **Blood pressure**
- **Skin thickness**
- **Insulin level**
- **BMI (Body Mass Index)**
- **Diabetes pedigree function**
- **Age**
- **Outcome** (0: Non-Diabetic, 1: Diabetic)

---

## 🛠️ Installation & Setup
### 🔹 Clone the Repository
```sh
git clone https://github.com/hendrix0731/Diabetes-Prediction.git
cd Diabetes-Prediction
```

### 🔹 Install Dependencies
Ensure you have Python and required libraries installed:
```sh
pip install numpy pandas scikit-learn
```

### 🔹 Run the Script
```sh
python project_3_diabetes_prediction.py
```

---

## 🎯 Model Performance
The model is evaluated using **accuracy score**:
- **Training Accuracy:** 78.66%
- **Test Accuracy:** 77.27%

_(result according to diabetes.csv)_

---

## 🖥️ Example Prediction
```python
input_data = (5,166,72,19,175,25.8,0.587,51)
prediction = classifier.predict(std_data)
print(prediction)
```
**Output:**
```
The person is diabetic
```

---

## 📌 Future Improvements
- Enhance accuracy using **hyperparameter tuning**
- Implement **Deep Learning models** for better performance
- Deploy as a **Web App** using Flask or FastAPI

---

## 🤝 Contributing
Pull requests are welcome! Feel free to open an issue for discussions.

---

## 📩 Contact
🔗 **GitHub:** [@hendrix0731](https://github.com/hendrix0731)  
🌍 **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/hendrix07?original_referer=https%3A%2F%2Fgithub.com%2Fhendrix0731)
