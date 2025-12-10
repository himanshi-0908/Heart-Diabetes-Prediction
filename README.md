

# **Heart & Diabetes Prediction System (ML + Streamlit)**

A simple ML web app that predicts **Heart Disease** and **Diabetes** using trained machine-learning models.
The app has a clean two-page UI built with **Streamlit**, where users can switch between both predictions.

---

## **🔍 What the App Provides**

### **1. Diabetes Prediction**

Takes inputs like:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### **2. Heart Disease Prediction**

Takes inputs like:

* Age, Sex
* Chest Pain Type
* Resting Blood Pressure
* Serum Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Max Heart Rate
* Exercise Induced Angina
* ST Depression
* Slope, Major Vessels, Thal

---

## **🖥️ Live Demo (if you want to add later)**

```
https://diseasespred-web.streamlit.app/
```

*(Add this only if your deployment is live)*

---

## **📦 Tech Stack**

* **Python**
* **Streamlit**
* **Scikit-learn**
* **Pandas / NumPy**
* **Pickle models (.pkl files)**

---

## **📁 Project Structure**

```
Heart-Diabetes-Prediction/
  ├── app.py
  ├── heart_model.pkl
  ├── diabetes_model.pkl
  ├── requirements.txt
  ├── streamlit.run.txt
  └── README.md
```

---

## **⚙️ Setup Instructions**

1. Open **Anaconda Navigator**
2. Go to **Environments**
3. Create a new environment named **Machine-Learning**
4. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

---

## **🚀 Run the App**

Use the full path saved in your `streamlit.run.txt`:

```
streamlit run /path/to/app.py
```

Replace the path with the actual location of your file.

---

## **📸 UI Preview**

**Diabetes Prediction Page**

![Diabetes UI]

**Heart Disease Prediction Page**

![Heart UI](./screenshots/heart.png)



---

## **🛠️ Future Improvements**

* Add more disease prediction models
* Improve UI/UX with charts
* Add explanation using SHAP/LIME
* Deploy on HuggingFace or AWS Lambda

---


