
# 🧠 Support Vector Machine (SVM) from Scratch – Diabetes Prediction

This project showcases a complete **Support Vector Machine (SVM) model built from scratch** in Python. The model is implemented manually without using `scikit-learn` and is packaged as a Python module for ease of use.

The SVM model is trained on real-world medical data to **predict whether a person is diabetic or not**.

---

## 🚀 What I Created

- ✅ Custom SVM algorithm (Python implementation)
- ✅ Training from scratch using hinge loss and gradient descent
- ✅ Standalone `.py` file that can be imported as a module
- ✅ Example usage in a Jupyter Notebook for diabetes prediction

---

## 📂 File Structure

- `svm_model.py` — Your custom SVM model class  
- `Support_Vector_Machine.ipynb` — Notebook demonstrating diabetes classification  
- `requirements.txt` — Required Python packages  

---

## ⚙️ How to Use the Model

1. **Download `SVM_classifier.py` to your local project folder**

2. **Import it in your script or notebook:**

```python
from SVM_classifier import SVM

# Create model instance
model = SVM(learning_rate=0.001, no_of_iterations=1000, lambda_parameter=0.01)

# Train the model
model.fit(X_train, y_train)

# Make predictions
predictions = model.predict(X_test)
```

3. **Required Parameters**:
   - `learning_rate`: Controls the step size in gradient descent
   - `no_of_iterations`: Number of iterations for training
   - `lambda_parameter`: Regularization parameter to avoid overfitting

---

## 📊 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧪 Dataset Overview

Health-related input features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

Target:  
- `1` = Diabetic  
- `0` = Non-diabetic

---

## 📈 Evaluation

The model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Visualization of prediction results

---

## 🧠 Key Learnings

- How Support Vector Machines work internally  
- Implementing hinge loss and gradient descent manually  
- Turning a machine learning algorithm into a reusable Python module  
- Applying the model to a real-world healthcare dataset

---

## 📝 License

This project is released under the **MIT License**.
