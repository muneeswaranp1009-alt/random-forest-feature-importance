#  Student Placement Prediction with Feature Importance Analysis

This project uses the Random Forest algorithm to predict student placement and analyze the importance of each feature contributing to the prediction.

## Features

- Student placement prediction using Random Forest
- Feature Importance Analysis
- Data preprocessing and encoding
- Model training and evaluation
- Accuracy Score calculation
- Classification Report
- Confusion Matrix
- Data visualization using Matplotlib
- Model saving with Joblib

---

##  Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Joblib

---

## Project Structure

```
student-placement-feature-importance-random-forest/
│
├── students_data.csv
├── placement_model.pkl
├── feature_importance.py
└── README.md
```

---

##  Dataset Features

The model uses the following input features:

- CGPA
- Aptitude Score
- Communication Skills
- Number of Projects
- Internship Status

### Target Variable

- Placement (Yes / No)

---

##  Feature Importance

The Random Forest model calculates the importance of each feature, helping identify which student attributes have the greatest impact on placement prediction.

Example output:

```
Feature Importance

CGPA             : 38.25%
Aptitude         : 24.80%
Communication    : 18.60%
Projects         : 11.15%
Internship       : 7.20%
```

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-placement-feature-importance-random-forest.git
```

Install dependencies:

```bash
pip install pandas matplotlib scikit-learn joblib
```

Run the project:

```bash
python feature_importance.py
```

---

##  Model Evaluation

The project evaluates the model using:

- Accuracy Score
- Classification Report
- Confusion Matrix

Visualizations include:

- Placement Count Chart
- CGPA vs Placement Scatter Plot
- Feature Importance Analysis

---

## Learning Outcomes

- Data Preprocessing
- Random Forest Classification
- Feature Importance Analysis
- Machine Learning Model Evaluation
- Data Visualization
- Model Serialization using Joblib

---

##  Future Improvements

- Add SHAP value explanations
- Interactive Feature Importance Dashboard
- Streamlit Web Application
- Compare Feature Importance across multiple ML models
- Deploy as a web service

---

##  Author

Developed as a Machine Learning project to predict student placement and analyze feature importance using the Random Forest algorithm.

⭐ If you found this project useful, consider giving it a star on GitHub!
