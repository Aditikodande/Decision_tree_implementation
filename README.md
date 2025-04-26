COMPANY:CODETECH IT SOLUTIONS
NAME:Aditi Kodande
INTERN ID::CT04DA652
DOMAIN:Machine learning
BATCH DURATION:April 10th, 2025 to May 10th, 2025. 
MENTOR NAME:NEELA SANTOSH
---

# Decision Tree Classifier on Iris Dataset 🌸🌳

This project builds a **Decision Tree Classifier** to classify different species of the Iris flower using the famous **Iris dataset** from `sklearn.datasets`.

---

## 📚 Project Structure

- **Import Required Libraries:**  
  Essential libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn are imported.

- **Load Dataset:**  
  The Iris dataset is loaded and converted into a pandas DataFrame for easy handling.

- **Explore and Preprocess Data:**  
  - Display the first few rows of the dataset.
  - Check for null or missing values.
  - Prepare features (X) and target labels (y).

- **Split the Data:**  
  Data is split into training and testing sets using `train_test_split` (80% train, 20% test).

- **Build and Train Model:**  
  A **Decision Tree Classifier** with `entropy` criterion and a maximum depth of 3 is built and trained.

- **Make Predictions:**  
  Predictions are made on the testing set.

- **Evaluate the Model:**  
  - Accuracy score
  - Classification report
  - Confusion matrix heatmap
  
- **Visualize the Decision Tree:**  
  The tree is visualized using `plot_tree`.

---

## 📦 Requirements

Install the required Python packages before running the project:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Make sure the required libraries are installed.
3. Run the Python script (`.py` file or Jupyter Notebook).
4. View the evaluation metrics and visualizations.

---

## 🎯 Results

- Model achieves high accuracy on the Iris dataset.
- Confusion Matrix and Classification Report are generated.
- Decision Tree is visualized clearly, showing splits based on feature values.

---

## 📈 Visualization Samples

- **Confusion Matrix**  
  Shows how well the model performs across each class.

- **Decision Tree Diagram**  
  Provides a detailed view of decision paths based on feature thresholds.

---

## 🔥 Key Parameters

- **Criterion:** `entropy`
- **Max Depth:** `3`
- **Random State:** `42` (for reproducibility)

---

## 🛠️ Future Improvements

- Perform hyperparameter tuning (e.g., `GridSearchCV`).
- Experiment with different splitting criteria (`gini` vs `entropy`).
- Cross-validation to avoid overfitting.
- Try different models (e.g., Random Forest).

---

## 🧠 About the Iris Dataset

The Iris dataset contains:
- 150 samples
- 4 features:  
  `sepal length`, `sepal width`, `petal length`, `petal width`
- 3 target classes:  
  `setosa`, `versicolor`, `virginica`

---

## 💬 Acknowledgements

- The Iris dataset is publicly available and widely used for educational purposes.
- Scikit-learn for machine learning tools.

---

Would you also like me to give a slightly shorter version if you want to keep it **really clean and simple**? 🚀
