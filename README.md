# credit-approval
# Credit Approval Prediction with Machine Learning

This project implements a machine learning pipeline to predict credit
approval or denial using a public synthetic financial risk dataset.
The focus of the project is on data preprocessing, model training,
validation, and deployment through an interactive Streamlit application.

## Technologies
- Python
- Pandas
- NumPy
- scikit-learn
- Streamlit

## Dataset
The model was trained using a public synthetic dataset focused on
financial risk for loan approval, available on Kaggle
("Financial Risk for Loan Approval").

The use of synthetic data ensures reproducibility of the project and
avoids the use of sensitive real-world financial information.

## Methodology
The project follows a structured data science workflow:

1. **Data preprocessing**
   - Data cleaning and refactoring
   - Feature selection and transformation
   - Outlier detection and removal using the Interquartile Range (IQR) method

2. **Model training**
   - Supervised classification model trained using scikit-learn
   - Hyperparameter tuning and evaluation

3. **Model evaluation**
   - Performance evaluation using standard classification metrics
   - Cross-validation to assess model generalization
   - Achieved an accuracy score of approximately **98%**

   > Note: The high accuracy is influenced by the synthetic nature of the dataset and is interpreted accordingly.

4. **Deployment**
   - The trained model is loaded into a Streamlit application
   - The app allows interactive inference with new input data

## Application
The Streamlit application provides:
- User-friendly input for credit application features
- Real-time prediction of approval or denial
- Visualization of model output for decision support


