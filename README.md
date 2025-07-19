# Support Vector Regression (SVR) Application  

This project demonstrates the implementation of **Support Vector Regression (SVR)** in Python using Scikit-learn. It focuses on understanding how SVR can model non-linear relationships by applying different kernel functions and comparing the results.  

---

## 🎯 Project Objective  

- Learn and apply the **SVR algorithm** for regression problems.  
- Explore the effect of different **kernel types (linear, polynomial, RBF)** on prediction performance.  
- Visualize the regression results and compare model fits.  

---

## 🧠 Methods & Workflow  

1. **Data Preparation**  
   - Load and preprocess the dataset.  
   - Scale the features for optimal SVR performance.  

2. **Model Training**  
   - Train SVR models with different kernels:
     - Linear
     - Polynomial
     - RBF (Radial Basis Function)

3. **Prediction & Visualization**  
   - Compare predicted vs actual values.  
   - Visualize regression curves to show how different kernels behave.  

4. **Evaluation**  
   - Check model performance visually and through basic metrics.

---

## 📂 Project Structure  

```
📂 SVR_Regression_Project
├── SVR_Uygulama.ipynb     # Jupyter Notebook with full implementation
├── data/                 # (Optional) dataset used
└── README.md             # Project documentation
```

---

## 📈 Technologies Used  

- **Python**  
- **NumPy, Pandas** for data handling  
- **Matplotlib** for visualization  
- **Scikit-learn** for SVR implementation and preprocessing  

---

## 🚀 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/akbatuhan/SVR_Regression.git
   cd SVR_Regression
   ```  

2. Install required libraries:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Open the notebook:  
   ```bash
   jupyter notebook SVR_Uygulama.ipynb
   ```  

---

## 🔮 Future Improvements  

- Hyperparameter tuning with **GridSearchCV**  
- Compare SVR with other regression models (Linear Regression, Decision Tree Regressor, etc.)  
- Add more evaluation metrics like **MSE, RMSE, R² Score**  

---

## 📚 References  

- [Scikit-learn SVR Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)  
- [Support Vector Regression Explanation](https://towardsdatascience.com/support-vector-regression-svr-explained-7e75493beb49)  

---
