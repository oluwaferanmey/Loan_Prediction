# **Loan Eligibility Prediction Project**

---

## **Overview**
This project uses machine learning to predict loan eligibility for applicants based on historical data. The system is designed to streamline loan approval processes, improve risk assessment, and enhance customer satisfaction.

---

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

---

## **Features**
- **Data Preprocessing**: Handles missing values, categorical encoding, and standardization of numerical features.
- **Feature Engineering**: Adds impactful features like income-to-loan ratio and credit history indicators.
- **Machine Learning Models**: Implements Logistic Regression, Random Forest, and Support Vector Machine (SVM).
- **Model Optimization**: Uses grid search to optimize hyperparameters for SVM.
- **Evaluation Metrics**: Includes accuracy, precision, recall, and F1-score for model assessment.
- **Deployment Ready**: Designed for integration into real-world loan processing systems.

---

## **Installation**
### **Prerequisites**
- Python 3.7 or higher
- Pip or Conda for dependency management

### **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-eligibility-prediction.git
   cd loan-eligibility-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python scripts:
   ```bash
   jupyter notebook
   ```

---

## **Usage**
1. Load the dataset by running the `data_preprocessing.py` script.
2. Train and test models using the `model_training.py` script.
3. Evaluate results and visualize metrics with the `evaluation.py` script.
4. Deploy the optimized model for predictions using `deployment.py`.

---

## **Model Performance**
- **Logistic Regression**:
  - Accuracy: **78%**
  - F1-Score: **0.75**
- **Random Forest**:
  - Accuracy: **77%**
  - F1-Score: **0.76**
- **Optimized SVM**:
  - Accuracy: **79%**
  - F1-Score: **0.78**

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
- **Tools**:
  - Jupyter Notebook
  - GridSearchCV
