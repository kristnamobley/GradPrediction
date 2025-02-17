# Graduation Prediction

## Overview
This project uses a machine learning model to predict whether high school students will graduate on time, based on historical data from students who have already graduated. The model was trained on various features, including GPA, attendance, and course completion rates. The goal of this project is to help predict students who might be at risk of not graduating on time and provide actionable insights to educators.

## Data
- **Training Data**: The model was trained using historical data of students who have already graduated.
- **Test Data**:The model is then applied to current student data to predict whether they will graduate on time.

### Features Used for Prediction:
- Feature 1: A key feature relevant to student performance.
- Feature 2: A metric related to student attendance.
- Feature 3: Information about student course completion.
- Feature 4: Behavioral information related to the student.
- Other Features: Indicators for enrollment in different special programs.


## Machine Learning Model
The project uses a **Decision Tree Classifier** from 'scikit-learn' to predict wether students will graduate on time if at all.

### Steps:
1. **Data Preparation**: Data from students who have already graduated was gather in SQL to create  table with studentids and columns including their data that would affect their graduation. Data was processedm cleaned and used for training the model.
2. **Model Training**:The model is trained on features such as grades, attendance, and course completion.
3. **Model Prediction**: The trained model is then used to make predictions on current student data to determine which students are likely to graduate on time.
