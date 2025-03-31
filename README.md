# **🔍 Crime Prediction using Machine Learning**

A machine learning project aimed at analyzing and predicting crime patterns using various features such as offender count, victim count, crime type, and area type.

## **📁 Project Structure**

CP_Project_V2/ 
    ├── datasets/ │ 
                  └── hate_crime.csv 
                  |__ updated_hate_crime.csv
    ├── source_code/ │ 
                     └── hate_crime_prediction_V2.html
                     |__ hate_crime_prediction_V2.ipynb
                     |__ hate_crime_prediction_V2.pdf 
    ├── dependencies/ │ 
                      └── requirements.txt 
    |__ .gitignore
    └── README.md


## **🎯 Objectives**

- Analyze correlations between crime-related features
- Use feature selection techniques to find the most impactful features
- Apply machine learning models such as Decision Tree and Random Forest
- Visualize feature importance and data relationships

## **📌 Selected Features**

Based on correlation analysis and feature importance from models:

| Feature Name             | Description                                 |
|--------------------------|---------------------------------------------|
| `total_offender_count`   | Total number of offenders in a crime        |
| `total_individual_victims` | Total number of victims involved         |
| `crime_type_violent`     | Whether the crime was violent or not       |
| `area_type_Urban`        | Indicates if the crime occurred in urban areas |

These were chosen for their consistently high scores across multiple feature importance analyses (Random Forest & Decision Tree).


## **📌 Selected Target Variables**
1. `bias_category_gender`
2. `bias_category_racial
3. `bias_category_religion`
4. `bias_category_other`

## **🧠 Models Used**

- ✅ Decision Tree Classifier
- ✅ Random Forest Classifier
- ✅ XGBoost Classifier

Performance comparison and feature importances are visualized through bar charts and heatmaps.

## **📊 Visual Results**

✅ Heatmaps and bar charts are included in the notebook to show:

- Correlation between features
- Model-based feature importance

> You can find these visualizations in `source_code/hate_crime_prediction_V2.ipynb`.

## **🚀 Getting Started**

1. Clone this repository:
   ```bash
   git clone https://github.com/LovelyPrinceGI/crime-prediction-using-ml.git

2. Create and activate the virtual environment:
    ```bash
    python -m venv dsai_venv
    dsai_venv\Scripts\activate

3. Install dependencies:
    ```bash
    pip install -r dependencies/requirements.txt

4. Run the notebook


## **🛠 Dependencies**
### Key packages:

- `pandas`

- `scikit-learn`

- `matplotlib`

- `seaborn`

- `streamlit (for optional app deployment)`

`Note`: All dependencies are listed in dependencies/requirements.txt.


### **Author**
- Patsakorn Tangkachaiyanunt 
- Shreeyukta Pradhanang