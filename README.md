# Using Customer Retail Dataset to Implement and Compare Machine Learning Models

## 📌 Project Overview

This project demonstrates the implementation and comparison of multiple Machine Learning classification algorithms using a customer retail dataset. It covers the complete Machine Learning workflow, including data preprocessing, visualization, model training, evaluation, and performance comparison.

## 🎯 Objective

The primary objective of this project is to:

* Explore and preprocess retail customer data.
* Train multiple supervised Machine Learning models.
* Compare model performance using standard evaluation metrics.
* Understand the strengths and limitations of different classification algorithms.

## 📂 Dataset Features

The dataset contains the following key attributes:

| Feature   | Description                          |
| --------- | ------------------------------------ |
| Quantity  | Number of items purchased            |
| UnitPrice | Price per item                       |
| Country   | Customer's country (Target Variable) |

## ⚙️ Project Workflow

### 1. Data Loading

* Load the dataset using Pandas.
* Explore dataset structure and basic statistics.

### 2. Data Preprocessing

* Handle missing values.
* Select relevant features.
* Encode the target variable (`Country`) using `LabelEncoder`.

### 3. Data Visualization

* Visualize customer distribution by country using Matplotlib.
* Gain insights into class distribution.

### 4. Data Splitting

* Split the dataset into:

  * 80% Training Data
  * 20% Testing Data
* Use stratified sampling to maintain class balance.

### 5. Feature Scaling

* Apply `StandardScaler` to normalize numerical features.

### 6. Model Training

The following Machine Learning algorithms are implemented:

* Logistic Regression
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)

### 7. Model Evaluation

Evaluate each model using:

* Accuracy Score
* Confusion Matrix

### 8. Performance Comparison

* Compare model accuracies using a bar chart.
* Identify the best-performing model.

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 91.4%    |
| Decision Tree       | 91.4%    |
| KNN                 | 90.8%    |

### Key Observations

* Logistic Regression and Decision Tree achieved the highest accuracy.
* KNN performed slightly lower but still delivered strong results.
* Confusion matrices provide detailed insights into class-wise predictions.

## 📈 Visualizations

The project includes:

* Customer Distribution by Country
* Model Accuracy Comparison Bar Chart
* Confusion Matrices for Each Model

## 🎓 Learning Outcomes

By completing this project, you will learn:

* Data preprocessing techniques
* Feature scaling and encoding
* Supervised Machine Learning algorithms
* Model evaluation methods
* Performance comparison and result interpretation
* Data visualization using Matplotlib

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## 🔧 Installation & Usage

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Add Dataset

Place the dataset file:

```text
customer_retail csv file.csv
```

inside the project directory.

### Run the Project

```bash
python main.py
```

### Output

The program will display:

* Model accuracy scores
* Confusion matrices
* Visualizations and comparison charts

## ✅ Conclusion

This project showcases the practical application of Machine Learning techniques on retail customer data. Logistic Regression and Decision Tree Classifier achieved the best performance with approximately 91% accuracy, while KNN produced competitive results. The project provides hands-on experience with the complete Machine Learning pipeline and serves as a strong foundation for future ML projects.

## 👨‍💻 Author

**Niranjan Varma**

GitHub: https://github.com/niranjanniru-max
