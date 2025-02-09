# Magadha Bank Loan Prediction

## Project Overview
This project focuses on predicting whether existing customers of **Magadha Bank** would opt for a personal loan. The bank aims to convert its **liability customers** into **personal loan customers** while ensuring they remain depositors. A previous marketing campaign by the bank had a **9% success rate**, encouraging the **retail marketing department** to develop more targeted campaigns to improve the success ratio within a minimal budget.

## Dataset and Preprocessing
The dataset provided includes customer details and historical banking data. The following preprocessing steps were performed:
- **Handling missing values**
- **Encoding categorical variables**
- **Feature scaling and transformation**
- **Splitting the dataset into training and testing sets**

## Exploratory Data Analysis (EDA)
EDA was conducted to:
- Identify key patterns and trends in customer data
- Visualize correlations between features and loan preferences
- Detect potential outliers and anomalies

## Machine Learning Models Used
Several supervised learning models were implemented and compared based on accuracy scores:
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Support Vector Classifier (SVC)**

After evaluating performance, **Random Forest** was chosen as the final model due to its superior accuracy. The model was further tested on unseen data to validate its correctness.

## Results and Conclusion
- The **Random Forest model** provided the highest accuracy among all tested algorithms.
- The model was successfully used to predict loan preferences of existing customers.
- Insights from this model can help Magadha Bank refine their **marketing strategies** for better customer targeting.

## Installation and Usage
To run this project on your local machine:
```sh
# Clone the repository
git clone https://github.com/your-username/magadha-bank-loan-prediction.git

# Navigate to the project directory
cd magadha-bank-loan-prediction

# Install required dependencies
pip install -r requirements.txt

# Run the main script
python main.py
```

## Future Enhancements
- Experiment with **hyperparameter tuning** for better model optimization.
- Implement **deep learning models** for more robust predictions.
- Deploy the model as a **web application** for real-time predictions.

## License
This project is licensed under the **MIT License**.

---
Feel free to contribute, raise issues, or suggest improvements!


