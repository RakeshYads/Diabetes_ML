# Diabetes_ML
This repository contains code and resources for predicting diabetes using machine learning techniques. The goal of this project is to build a predictive model that can accurately identify whether a patient has diabetes based on diagnostic measurements included in the dataset.

### Dataset
The dataset used in this project is the Pima Indians Diabetes Database, sourced from the UCI Machine Learning Repository. It consists of several medical predictor variables and one target variable, Outcome, which indicates whether the patient has diabetes (1) or does not (0).

### Approach

    - Data Preprocessing: Exploratory data analysis, handling missing values, and feature engineering.
    - Model Selection: Evaluating various machine learning algorithms such as Logistic Regression, Random Forest, and Support Vector Machines.
    - Model Evaluation: Comparing models using metrics like accuracy, precision, recall, and F1-score. Handling class imbalance using techniques like SMOTE.
    - Deployment: Once the best model is identified, creating a simple web application or API using FastAPI for making predictions.

### Files

   - health care diabetes.csv: Dataset used for training and evaluation.
   - Final_Project_Diabetes.ipynb: Jupyter notebook containing the Python code for data preprocessing, model training, and evaluation.
    app.py: FastAPI web application for making predictions using the trained model.

### Usage

   1. Clone the repository:

    ```bash

	git clone https://github.com/yourusername/diabetes-prediction.git
	```
   2. Install the required libraries:

	```bash
	pip install -r requirements.txt
	```
   3. Run the Jupyter notebook Final_Project_Diabetes.ipynb to see the detailed analysis and model building process.

   4. Explore the FASTAPI web application by running:

	```bash
        python app.py
	```
   5. Navigate to http://localhost:8000 to interact with the prediction interface.

### Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements or suggestions.

For questions or support, please contact [Rakesh Yadav](https://www.linkedin.com/in/rakesh-yadav-556724118/)
