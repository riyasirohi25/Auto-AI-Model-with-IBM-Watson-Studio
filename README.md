# Titanic Survival Prediction using IBM Watson AutoAI
Built an ML model using IBM Watson Studio's AutoAI to predict Titanic passenger survival. The tool automated data preprocessing, feature engineering, model selection, and tuning. Based on the Kaggle Titanic dataset, the project showcases end-to-end Auto ML workflow with minimal coding.

This project demonstrates how IBM Watson Studio’s AutoAI can be used to automatically build and optimize machine learning models for predicting Titanic passenger survival. With minimal coding, AutoAI takes care of data preprocessing, feature engineering, model selection, and tuning — making it ideal for rapid prototyping.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [AutoAI Workflow](#autoai-workflow)
- [Results](#results)
- [How to Run](#how-to-run)
- [Screenshots (Optional)](#screenshots-optional)
- [Credits](#credits)

---

## About the Project

This machine learning project leverages IBM Watson Studio's AutoAI to predict survival outcomes for passengers aboard the Titanic. The AutoAI tool automatically handles tasks like data preparation, pipeline building, and model optimization. The goal is to demonstrate how powerful automated machine learning (AutoML) can be when applied to a classic dataset like Titanic.

---

## Dataset

- **Name:** Titanic - Machine Learning from Disaster  
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)  
- **Description:** The dataset contains information about passengers aboard the RMS Titanic, such as age, sex, class, fare, and whether they survived.

| Column | Description |
|--------|-------------|
| PassengerId | Unique ID for each passenger |
| Survived | 0 = No, 1 = Yes |
| Pclass | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Name of passenger |
| Sex | Gender |
| Age | Age in years |
| SibSp | siblings/spouses aboard |
| Parch | parents/children aboard |
| Ticket | Ticket number |
| Fare | Passenger fare |
| Cabin | Cabin number |
| Embarked | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## Technologies Used

- **IBM Watson Studio**
- **AutoAI**
- **Python (for optional preprocessing or visualizations)**
- **Jupyter Notebooks/ Google Colab (optional)**

---

## AutoAI Workflow

1. **Upload the Titanic dataset** to your IBM Watson Studio project.
2. **Create a new AutoAI experiment** and link the uploaded dataset.
3. **Select the target column**: `Survived`
4. AutoAI performs:
   - Automated data cleaning and preprocessing
   - Feature transformation and selection
   - Model generation with multiple algorithms
   - Hyperparameter optimization
   - Leaderboard evaluation of all models
5. **Best model is selected** based on accuracy and performance.
6. Export the model pipeline for deployment or integration.

---

## Results

- **Target Column:** `Survived`
- **Best Performing Model:** XGBoostClassifier
- **Accuracy Achieved:** _(83.3%)_
- **Feature Importance:** AutoAI identified key factors like `Sex`, `Pclass`, `Fare`, and `Age` as strong predictors of survival.

You can also view the leaderboard inside Watson Studio to compare precision, recall, F1-score, and ROC-AUC for all generated models.

---

## How to Run

1. Create an account on [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio).
2. Create a new **project**.
3. Upload the Titanic dataset (`train.csv`).
4. Launch a new **AutoAI experiment** inside the project.
5. Select the uploaded dataset and specify the prediction column as `Survived`.
6. Run the experiment and review the leaderboard.
7. Export the best-performing model pipeline for deployment or analysis.

---

## Screenshots

### 🔄 AutoAI Pipeline
![AutoAI Pipeline](https://github.com/riyasirohi25/Auto-AI-Model-with-IBM-Watson-Studio/blob/main/Screenshot%202025-07-09%20233927.png?raw=true)

### 🏆 Leaderboard
![Leaderboard](https://github.com/riyasirohi25/Auto-AI-Model-with-IBM-Watson-Studio/blob/main/Screenshot%202025-07-09%20233942.png?raw=true)

### 📊 Feature Importance
![Feature Importance](https://github.com/riyasirohi25/Auto-AI-Model-with-IBM-Watson-Studio/blob/main/Screenshot%202025-07-09%20235714.png?raw=true)

---

## Credits

- **Dataset:** [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- **Platform:** [IBM Watson Studio AutoAI](https://www.ibm.com/cloud/watson-studio/autoai)
- **Inspiration:** To explore no-code/low-code AI model development and AutoML workflows.

---


