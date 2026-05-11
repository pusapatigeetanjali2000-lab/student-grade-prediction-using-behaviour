# student-grade-prediction-using-behaviour
This project aims to predict the final academic performance (grades) of students by analyzing a variety of factors including demographic data, social backgrounds, and academic history. Using Machine Learning regression techniques, the system identifies such as study time, parental education, and previous exam score forecast the final grade ($G3$)
🚀 Key FeaturesData Preprocessing: Handles categorical variables via 
One-Hot Encoding and scales numerical features for better model convergence.
Exploratory Data Analysis (EDA): Visualizes correlations between lifestyle factors 
(like alcohol consumption or internet access) and academic results.Predictive Modeling: Implements and compares multiple algorithms:Linear RegressionRidge & Lasso RegressionRandom Forest RegressorWeb Interface (Optional): A Flask/Streamlit dashboard where users can input student data to get instant grade predictions.
📊 Dataset OverviewThe project utilizes the UCI Student Performance Dataset, which includes
:Attributes: 33 features (e.g., studytime, failures, absences, famrel, freetime).Target Variable: $G3$ (Final Grade).Domain: Data collected from two schools (Math and Portuguese subjects).🛠️ Tech StackLanguage:
PythonLibraries:Pandas & NumPy (Data Manipulation)Scikit-Learn (Model Training & Evaluation)Matplotlib & Seaborn (Data Visualization)
Flask (Deployment/API)📈 
MethodologyData Ingestion: Reading raw CSV data and performing initial integrity checks.Feature Engineering: Dropping low-correlation features and handling outliers in 'absences'.Model Selection: Training various models and evaluating them using Mean Absolute Error (MAE) and R-squared ($R^2$) scores.Hyperparameter Tuning: Optimizing model parameters to minimize error.
