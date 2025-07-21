<h1 align = "center"> 📊 Bank Marketing Decision Tree Classifier </h1> 

This project involves building a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data. The dataset used is the Bank Marketing dataset from the UCI Machine Learning Repository, accessed via [Prodigy InfoTech’s GitHub](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203).


## 📁 Dataset Overview

- **Source:** UCI Machine Learning Repository
- **Filename:** bank.csv
- **Attributes:** Age, job, marital status, education, default, balance, housing loan, etc.
- **Target variable:** y
  - yes: Subscribed to term deposit  
  - no: Not subscribed


## 🚀 Objective

To train and evaluate a Decision Tree Classifier that predicts the likelihood of a customer subscribing to a term deposit based on their profile.


## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


## 📌 Project Workflow

1. **Import Libraries**  
2. **Load the Dataset**
3. **Data Exploration & Preprocessing**
   - One-hot encoding for categorical variables
   - Feature-target split
4. **Model Building**
   - Decision Tree using `entropy` criterion
   - Train-test split
5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report
6. **Visualization**
   - Decision tree plotted using `plot_tree()`


## 🧪 Model Evaluation

The model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)


## 📊 Visualization

The decision tree structure is plotted using matplotlib to understand decision paths.


## 📈 Results

- **Accuracy Score:** ~88%
- **Precision for 'yes':** 0.70
- **Top Features Influencing Prediction:** Duration, month, balance, contact
