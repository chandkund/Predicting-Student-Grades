# 🎓 Predicting Student Grades

## Overview

This project predicts student grades (G1, G2, G3) based on various features such as demographic information, study habits, family background, and other academic factors. The aim is to develop a predictive model that can assist in identifying students who may need additional support.

## Project Workflow

1. **Data Exploration**  
   - Analyzed the distribution and relationships between features like study time, family support, and internet access.  
   - Visualized the data to understand patterns and detect any anomalies.  

2. **Data Preprocessing**  
   - Cleaned and prepared the dataset by handling missing values and encoding categorical variables.  
   - Scaled numerical features to ensure optimal model performance.  

3. **Model Implementation**  
   - Built regression models to predict student grades (G1, G2, G3).  
   - Experimented with algorithms like Linear Regression, Random Forest Regressor, and Support Vector Machines.  

4. **Model Evaluation**  
   - Evaluated model performance using metrics such as Mean Squared Error (MSE) and R-squared.  
   - Selected the best model based on predictive accuracy for future student grade predictions.  

## Datasets

The dataset includes the following features:  
- **school**: The school the student attends.  
- **sex**: Gender of the student.  
- **age**: Age of the student.  
- **address**: Type of residential address.  
- **famsize**: Family size.  
- **Pstatus**: Parent's cohabitation status.  
- **Medu**: Mother's education level.  
- **Fedu**: Father's education level.  
- **Mjob**: Mother's job.  
- **Fjob**: Father's job.  
- **reason**: Reason to choose the current school.  
- **guardian**: Student's guardian.  
- **traveltime**: Time taken to travel to school.  
- **studytime**: Weekly study time.  
- **failures**: Number of past class failures.  
- **schoolsup**: Extra educational support.  
- **famsup**: Family educational support.  
- **paid**: Extra paid classes.  
- **activities**: Extracurricular activities.  
- **nursery**: Attended nursery school.  
- **higher**: Wants to pursue higher education.  
- **internet**: Internet access at home.  
- **romantic**: Relationship status.  
- **famrel**: Quality of family relationships.  
- **freetime**: Free time after school.  
- **goout**: Going out with friends.  
- **Dalc**: Workday alcohol consumption.  
- **Walc**: Weekend alcohol consumption.  
- **health**: Current health status.  
- **absences**: Number of school absences.

## Target Columns
- **G1**: First period grade.  
- **G2**: Second period grade.  
- **G3**: Final grade.

## Installation

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/chandkund/Predicting Student Grades.git
   ```  
2. **Navigate to the project directory**:  
   ```bash
   cd Predicting Student Grades
   ```  
3. **Install required packages**:  
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the script to predict student grades:  
```bash
python Predicting Student Grades.py
```

## Results

The project successfully predicted student grades using various regression models. The best model provided accurate predictions of G1, G2, and G3, highlighting the importance of factors like study time, family support, and alcohol consumption.
