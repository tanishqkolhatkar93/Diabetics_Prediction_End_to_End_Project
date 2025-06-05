# 🧠 Diabetes Prediction Web App

An end-to-end machine learning project that predicts whether a person is diabetic using **Support Vector Machine (SVM)** with a **Linear Kernel**. The app is built and deployed using **Streamlit** for an intuitive user interface.

---

## 📦 Project Structure

```
📁 Project Root
│
├── Deploying_Machine_Learning_model_using_Streamlit.ipynb   # Notebook used for training & saving the model
├── app.py                                                  # Streamlit web app
├── diabetes.csv                                            # Dataset (PIMA Indian Diabetes)
├── trained_model.sav                                       # Pickled SVM model
└── README.md                                               # Project documentation
```

---

## 🔍 Problem Statement

This app helps predict the likelihood of diabetes in an individual based on diagnostic measurements like glucose level, insulin level, BMI, etc.

---

## 🎯 Key Features

- **Model Used:** Support Vector Machine (SVM) with Linear Kernel
- **Training Accuracy:** 78%
- **Framework:** Streamlit
- **Input Fields:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

- **Output:**  
  ➤ “**The person is diabetic**”  
  ➤ “**The person is not diabetic**”

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/tanishqkolhatkar93/diabetes-prediction-streamlit.git
cd diabetes-prediction-streamlit
```

### 2. Install Dependencies

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

<sub>If `requirements.txt` doesn't exist, you can install manually:</sub>

```bash
pip install streamlit scikit-learn pandas numpy
```

### 3. Run the Streamlit App

```bash
streamlit run app.py
```

The app will launch at `http://localhost:8501` in your browser.

---

## 🧠 Model Details

- **Algorithm:** Support Vector Machine (SVM)
- **Kernel:** Linear
- **Metric Used:** Accuracy Score (78%)

---

## 📊 Dataset Info

- **Source:** PIMA Indian Diabetes Dataset
- **Rows:** 768
- **Columns:** 8 Features + 1 Target

---

## 📷 App Preview

> ✨![Uploading Screenshot 2025-06-05 212454.png…]()


---

## 🛠 Technologies Used

- Python
- Scikit-learn
- Streamlit
- Pandas
- NumPy
- Jupyter Notebook
- Pickle (for model saving/loading)

---

## 📬 Author

**Tanishq Kolhatkar**  
📧 tanishqkolhatkar93@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/tanishq93/) 

---

## 📃 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## ⭐️ Show Your Support

If you found this project helpful, give it a ⭐ on GitHub!
