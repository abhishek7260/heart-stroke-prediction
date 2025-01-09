# Heart-Stroke-Prediction

**Overview**
In this project, we apply machine learning techniques to predict stroke risk based on various health parameters. The dataset is cleaned, processed, and analyzed using various data analysis techniques, followed by training multiple machine learning models to classify stroke risk.

## Dataset

The dataset used in this project is the Stroke Prediction Healthcare Dataset, which contains several features including:

- age: Age of the individual

- gender: Gender of the individual

- hypertension: Whether the person has hypertension

- heart_disease: Whether the person has heart disease

- ever_married: Whether the person has ever been married

- work_type: Type of work the person does

- Residence_type: Urban or rural residence

- smoking_status: Smoking status of the individual

- bmi: Body Mass Index

- avg_glucose_level: Average glucose level

The target variable is stroke, which indicates whether the individual has had a stroke (1) or not (0).

## Technologies Used

**Python:**The primary programming language for data manipulation and model building.
**pandas:** For data manipulation and cleaning.
**matplotlib** and **seaborn:** For data visualization.
**scikit-learn:** For machine learning model building, evaluation, and metrics.
**Jupyter Notebook:** For interactive coding and analysis.

**Steps Taken**
  1. **Data Loading:**
     - Loaded the dataset using pandas read_csv function.
  2. **Data Cleaning and Preprocessing:**
     - Dropped the id column since it doesn't contribute to the prediction.
     - Converted age to integer and handled missing values in the bmi column.
     - Encoded categorical features such as gender, ever_married, work_type, 
       Residence_type, and smoking_status using label encoding.
  3. **Data Exploration:**
     - Analyzed the correlation between various features and the target variable (stroke).
     - Visualized data using count plots, line plots, and heatmaps to gain insights into feature relationships.
  4. **Modelling:**
     - Split the dataset into training and testing sets using train_test_split.
     - Trained several machine learning models, including:
         - Logistic Regression
         - K-Nearest Neighbors (KNN)
         - Support Vector Classifier (SVC)
         - Random Forest Classifier
   5. **Model Evaluation:**
      - Used various metrics to evaluate model performance like accuracy score,f1 score.
      - Visualized confusion matrices and compared the performance of the models.
        
# Modeling

Four machine learning models were tested:

- Logistic Regression: A linear model used for binary classification.
- Support Vector Machine (SVM): A powerful classifier for high-dimensional data.
- K-Nearest Neighbors (KNN): A non-parametric algorithm for classification based on proxim
ity.
- Random Forest Classifier: A decision tree-based ensemble method.
# Results
  [Uploading Heart_Stroke_Prediction.ipynb…]()![download (3)](https://github.com/user-attachments/assets/34bd94d8-fbee-4ad3-86cd-0209c8192ceb)
- Random Forest Classifier performed best in terms of accuracy as seen in the comparison bar chart.
   - Accuracy of Random Forest Classifier:  **0.9403**
  
