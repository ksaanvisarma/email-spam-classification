## Email-spam-classification
Machine learning project that compares multiple classification models to detect spam emails using accuracy, precision, recall, F1-score, and cross-validation.

### Overview
This project uses machine learning to classify emails as spam or non-spam. It compares multiple classification models and evaluates their performance using accuracy, precision, recall, F1-score, and cross-validation.

### Dataset
The project uses the [Email Spam Classification Dataset](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv) from Kaggle.

### Models
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Linear Support Vector Machine (SVM)
- Random Forest

### Evaluation
Models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Stratified 5-fold cross-validation
- Confusion matrices

### How to Run
1. Download or clone this repository.
2. Open `email_spam.ipynb` in Google Colab or Jupyter Notebook.
3. Download the dataset from Kaggle and follow the notebook's setup instructions.
4. Run the notebook cells in order.

### Tools
Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn
