# 🍬 Diabetes Prediction with Machine Learning

This project predicts whether a person has diabetes based on diagnostic measurements. It uses the **Pima Indians Diabetes Dataset** and is implemented in a Jupyter Notebook using common data science libraries.

## 📊 Dataset

Source: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
The CSV file is included in the `data` folder.  
Shape: 768 rows × 9 columns

## ⚙️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## 🗂️ Project Structure

- `notebooks/` — Jupyter notebook with the full analysis and model training  
- `data/` — Dataset files (CSV)  
- `requirements.txt` — List of required Python packages  
- `.gitignore` — Files and folders to ignore in git  

## 🚀 How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/alirazmjooei/diabetes-prediction.git
   cd diabetes-prediction
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:  
   ```bash
   jupyter notebook notebooks/diabetes_prediction.ipynb
   ```

## 📈 Model Evaluation

I evaluated the Random Forest classifier on the diabetes dataset using several important metrics and visualizations:

- **Accuracy:** 72% overall accuracy on the test set.  
- **Classification Report:** Includes precision, recall, and F1-score for both classes (diabetic and non-diabetic).

### 🔍 Key Visualizations

1. **🧮 Confusion Matrix:**  
   Shows the counts of true positive, true negative, false positive, and false negative predictions, helping to understand the types of errors the model makes.

2. **⭐ Feature Importance:**  
   Displays which features (e.g., glucose level, BMI) have the most impact on the model’s predictions, aiding interpretability.

3. **📉 ROC Curve:**  
   Illustrates the trade-off between true positive rate and false positive rate across different classification thresholds, with the Area Under Curve (AUC) indicating overall model performance.

These visualizations provide insights into the model’s strengths and weaknesses, ensuring a comprehensive evaluation beyond simple accuracy.
