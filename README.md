# Credit Card Fraud Detection Using Machine Learning 💳🚫

## 📝 Description 
This project focuses on developing a machine learning model for credit card fraud detection. The model is designed to identify fraudulent credit card transactions based on various features available in the dataset. The goal is to improve the accuracy of fraud detection and minimize the financial losses caused by fraudulent activities.

## ⌛ Dataset 
The dataset used for this project is named 'creditcard.csv'. It contains historical credit card transactions with labeled fraud (1) and non-fraud (0) cases.

## 🎯 Approach 
The project follows these key steps:
1. Data Preprocessing: The dataset is loaded, and initial exploratory data analysis is performed, including checking the shape, displaying the top and bottom rows, and checking for null values.
2. Feature Scaling: The 'Amount' column is standardized using the StandardScaler to bring it to a similar scale as the other features. The 'Time' column is dropped since it is not relevant for modeling.
3. Handling Imbalanced Dataset: Two techniques are used to handle the imbalanced class distribution - undersampling and oversampling. Both techniques are evaluated separately to compare their performance.
4. Model Training: Three classification models are trained on the preprocessed data - Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.
5. Model Evaluation: The models' performance is evaluated using various metrics, including accuracy, precision, recall, and F1-score, to assess their effectiveness in detecting credit card fraud.

## 📥 Installations 
To run this project, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- pandas
- seaborn
- scikit-learn
- imbalanced-learn

## ⚙️ Setup 
1. Clone the repository to your local machine.
2. Install the required dependencies using the following command:
   ```
   pip install pandas seaborn scikit-learn imbalanced-learn
   ```
3. Run the Jupyter Notebook file 'Credit_Card_Fraud_Detection.ipynb' to perform data preprocessing, model training, and evaluation.
4. Optionally, you can use the GUI by executing the Python script 'credit_card_fraud_detection_gui.py' to make predictions on new data.

## 🔧 Requirements 
The project requires the following libraries:
- pandas
- seaborn
- scikit-learn
- imbalanced-learn

## 🚀 Technology Used 
- Python
- Jupyter Notebook
- pandas (Data Manipulation Library)
- seaborn (Data Visualization Library)
- scikit-learn (Machine Learning Library)
- imbalanced-learn (Imbalanced Data Handling Library)

## ▶️ Run 
To execute the project, follow the setup instructions and run the code cells in the Jupyter Notebook file. Additionally, you can use the GUI to make credit card fraud predictions on new data.

---

📝 I frequently create content focused on complete projects in the realm of data science using Python and R.

💬 Feel free to inquire about data science, computer vision, Python, and R.

---

<p align="Right">(◕‿◕) Thank you for exploring my GitHub project repository. 👋</p>
