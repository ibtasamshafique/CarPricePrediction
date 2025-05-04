Data Science Project
==============================
DataScience Project Used Car Price Prediction

Used car price prediction
------------

Here is the project description with research questions and hypotheses:

```md
In my project I will investigate if it is possible to predict the used car price based on its features. As a basis I will use the [Used Car Price](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset/data) dataset. I will then train a classifier to predict the used car price based on its features. I will use the following research questions and hypotheses to guide my project:

Research Questions:
   - RQ1: What are the most influential factors in determining the price of a used car?
   - RQ2: How do specific attributes, such as mileage, fuel type, and accident history, correlate with the resale value of vehicles?
   - RQ3: Can machine learning models accurately predict the price of a used car based on its features?

Hypotheses:
   - H1: A vehicle's mileage has a stronger negative correlation with its price than its manufacturing year.
   - H2: Cars with clean titles are priced significantly higher than cars with a history of accidents.
   - H3: A supervised regression model (e.g., Random Forest Regressor) will predict used car prices more accurately than a baseline linear regression model.
```

In the following project, the dataset from:
 https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset/data
 is used.

 All results are summarized in main.ipynb . Concrete and detailed analysis results can be found in the corresponding notebooks. The notebooks should be executed in the structure or order shown (from top to bottom).

Project Structure:
```
├── data
│   ├── processed      <- used_cars_cleaned.csv The final, canonical data sets for modeling
│   └── raw            <- used_cars.csv The original dataset.
│
├── notebooks          <- Models_Evaluations.ipynb
│                      <- EDA_Visualization.ipynb
│                      <- pre_processing.ipynb
│
├── README.md          <- Explaining the project and how to run the code.
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                          generated with `pip freeze > requirements.txt`

```

Reproduciblity Instructions
------------
To reproduce this project, clone the repository, install the required dependencies using pip install -r requirements.txt, and run the notebooks inside the notebooks/ folder in the following order: Pre_Processing.ipynb, EDA_Visualization.ipynb, and Models_Evaluations.ipynb. Make sure the raw dataset (used_cars.csv) is placed in src/data/. The cleaned dataset (used_cars_cleaned.csv) will be generated during preprocessing.
