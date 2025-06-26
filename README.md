# 🌸 Iris Flower Classification Project

This project demonstrates how to classify **Iris flower species** using various **machine learning algorithms**.  
We use the famous **Iris dataset** which contains measurements of sepals and petals for three different species:  
**Setosa**, **Versicolor**, and **Virginica**.

---

## 📁 Dataset

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- Features:
  - `SepalLengthCm`
  - `SepalWidthCm`
  - `PetalLengthCm`
  - `PetalWidthCm`
  - `Species` (Target)

---

## 🧪 Objective

To build ML models that can **accurately classify** the species of an Iris flower using the four numerical features.

---

## 🧹 Steps Covered

1. **Data Preprocessing**
   - Checked for missing values
   - Encoded target labels
2. **Exploratory Data Analysis (EDA)**
   - Pairplots and histograms
   - Correlation heatmap
3. **Model Training**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Decision Tree Classifier
4. **Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report
5. **Visualization**
   - Model comparison
   - Confusion matrix heatmaps

---

## ✅ Results

| Model                 | Accuracy |
|----------------------|----------|
| Support Vector Machine (SVM) | 100%     |
| K-Nearest Neighbors (KNN)    | 100%     |
| Logistic Regression          | ~97%     |
| Decision Tree                | ~97%     |

- SVM and KNN delivered **perfect accuracy** on the test set.
- Most confusion occurred between *Versicolor* and *Virginica*.
- Petal features were the most important for classification.

---

## 🔮 Future Scope

- Add **Random Forest**, **XGBoost**, or **Ensemble methods**
- Perform **Hyperparameter Tuning** using `GridSearchCV`
- Use **Cross-validation** for robustness
- **Deploy model** using Streamlit or Flask
- Experiment with **image-based iris data** using CNNs

---

## 📊 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- FPDF (for generating PDF reports)

---

## 📌 How to Run

1. Clone this repository  
2. Install dependencies using `pip install -r requirements.txt`  
3. Run `iris_classification.ipynb` in Jupyter Notebook  
4. View the results and generated report

---

## 📄 PDF Report

A detailed PDF report is included covering:
- Problem Statement
- Exploratory Analysis
- Model Building
- Results
- Conclusion & Future Work

---

## 👨‍💻 Author

**Arjav Jain**  
BCA Student | Data Science Enthusiast  
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)

---

⭐ *If you found this helpful, consider giving a star to the repo!*
