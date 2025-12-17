📊 Student Purchase Prediction using Machine Learning
📌 Project Description
This project focuses on predicting whether a student is likely to purchase an electronic product within the next 6 months using survey-based data.
It demonstrates a complete machine learning pipeline, including data preprocessing, model training, evaluation, and interpretation.
________________________________________
🎯 Objective
To build and evaluate machine learning models that can accurately predict student purchase intent based on demographic, financial, and behavioral factors.
________________________________________
📂 Dataset Information
•	Type: Primary survey data
•	Records: 500+
•	Features: Mix of categorical and numerical variables
•	Target Variable:
Are you planning to purchase a new product within the next 6 months?
o	Yes → 1
o	No → 0
________________________________________
⚙️ Technologies & Tools
•	Language: Python
•	Libraries:
o	Pandas
o	NumPy
o	Scikit-learn
o	Matplotlib
o	Seaborn
________________________________________
🔄 Project Workflow
1.	Data loading and inspection
2.	Data cleaning and preprocessing
3.	Encoding categorical variables
4.	Feature–target separation
5.	Model training
6.	Evaluation using multiple train–test splits
7.	Model comparison and selection
8.	Result interpretation
________________________________________
🤖 Machine Learning Models Used
•	Logistic Regression
•	Decision Tree Classifier
•	Random Forest Classifier
________________________________________
📊 Model Evaluation
📌 Performance Comparison of Machine Learning Models
Models were evaluated using accuracy, precision, recall, and F1-score.
Among all models, Random Forest consistently performed the best.
📈 Random Forest Accuracy Across Different Train–Test Splits
To ensure robustness, Random Forest was tested on multiple train–test splits:
•	85% Train / 15% Test
•	80% Train / 20% Test
•	75% Train / 25% Test
•	70% Train / 30% Test
The performance remained stable across all splits.
________________________________________
📉 Confusion Matrix
A confusion matrix was generated for the 75–25 train–test split to analyze classification performance in detail.
________________________________________
⭐ Feature Importance
Feature importance analysis was performed using Random Forest to identify the most influential factors affecting student purchase decisions.
________________________________________
✅ Key Results
•	Best accuracy achieved: ~63%
•	Best F1-score: ~0.74
•	High recall for identifying potential buyers
•	Random Forest selected as the final model
________________________________________
🧠 Key Learnings
•	Evaluating multiple train–test splits improves model reliability
•	F1-score and recall are important for imbalanced datasets
•	Random Forest performs well on survey-based categorical data
________________________________________
🚀 Future Improvements
•	Handle class imbalance using advanced techniques
•	Perform hyperparameter tuning
•	Deploy the model using a web application
•	Expand dataset size for better accuracy

