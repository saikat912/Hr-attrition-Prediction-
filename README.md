# HR Analytics Real-Time Project

Welcome to the **HR Analytics Real-Time Project** repository! This project focuses on analyzing employee attrition data to uncover valuable insights and build predictive models that help organizations retain talent and improve workplace satisfaction.

---

## **Table of Contents**
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Key Features](#key-features)
- [Installation](#installation)
- [Project Workflow](#project-workflow)
- [Visualizations and Insights](#visualizations-and-insights)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Contributing](#contributing)
- [License](#license)

---

## **Overview**
Employee attrition is a critical issue for organizations, impacting productivity and costs. This project leverages data science techniques to analyze employee-related factors contributing to attrition, enabling data-driven decision-making.

The analysis includes:
- Exploratory Data Analysis (EDA) to identify trends and patterns.
- Predictive modeling using machine learning algorithms.
- Insights into key factors influencing attrition, such as age, department, and work-life balance.

---

## **Dataset Description**
The dataset contains information about employees, including:
- Demographics (e.g., age, gender, education).
- Job-related factors (e.g., department, job level, business travel).
- Performance metrics (e.g., years at company, training times).
- Attrition status (Yes/No).

### Sample Columns:
| Column Name             | Description                          |
|-------------------------|--------------------------------------|
| Age                    | Employee's age                      |
| Attrition              | Whether the employee left (Yes/No)  |
| Department             | Department of the employee          |
| TotalWorkingYears      | Total years of work experience      |
| WorkLifeBalance        | Rating of work-life balance         |

---

## **Key Features**
1. **Exploratory Data Analysis (EDA):**
   - Visualizing attrition trends across various demographics.
   - Correlation heatmaps for feature relationships.

2. **Predictive Modeling:**
   - Machine learning algorithms like Random Forest for classification.
   - Handling imbalanced datasets using SMOTE.

3. **Insights Generation:**
   - Identifying key contributors to attrition.
   - Visual comparisons of attrition rates across departments, genders, etc.

4. **Optimization:**
   - Hyperparameter tuning using GridSearchCV for model improvement.

---

## **Installation**
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/hr-analytics-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hr-analytics-project
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Project Workflow**
1. **Data Preprocessing:**
   - Handling missing values.
   - Label encoding categorical variables.
2. **Exploratory Data Analysis:**
   - Generating visual reports using tools like `seaborn` and `matplotlib`.
3. **Feature Engineering:**
   - Removing irrelevant features.
   - Scaling numerical data.
4. **Model Building:**
   - Training models like Random Forest.
   - Evaluating performance with metrics like accuracy and classification reports.
5. **Optimization:**
   - Hyperparameter tuning for better predictions.

---

## **Visualizations and Insights**
### Example Visualizations:
1. **Attrition by Age:**
   ![Attrition vs Age](https://github.com/saikat912/Hr-attrition-Prediction-/blob/c438c216dc41758fd5b74c561104827b1a13977a/download.png):**
   ![Attrition vs Department](images/attritionCorrelation Heatmap:**
   ![Correlation Heatmap](images/correlation_heatalizations help identify patterns such as higher attrition rates in specific age groups or departments.

---

## **Modeling and Evaluation**
### Algorithms Used:
- Random Forest Classifier
- Hyperparameter tuning via GridSearchCV

### Model Evaluation Metrics:
| Metric            | Train Set | Test Set |
|-------------------|-----------|----------|
| Accuracy          | 95%       | 89%      |
| Precision         | 92%       | 87%      |
| Recall            | 90%       | 85%      |

The model effectively predicts employee attrition while maintaining a balance between precision and recall.

---

## **Contributing**
We welcome contributions to enhance this project! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature-name
   ```
4. Open a pull request with a detailed description of your changes.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Let’s work together to make workplaces better by leveraging data-driven insights! 🚀

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/15804853/1610b3fb-7311-481a-8eda-e5bb239d1117/Domain_HR_Analytics_Real_Time_Project.ipynb

