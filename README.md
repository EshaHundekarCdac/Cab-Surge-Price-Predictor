# Cab Surge Price Predictor 🚕

An end-to-end Machine Learning project that predicts ride-sharing prices by analyzing historical cab ride and weather data. 

## Project Overview
This project builds a predictive model to understand the factors driving surge pricing in rideshare services. By integrating external weather conditions with ride metrics, the model achieves an R² score of ~0.94.

## Technologies Used
* **Languages:** Python
* **Libraries:** pandas, scikit-learn, matplotlib, seaborn, joblib
* **Tools:** Jupyter Notebook, Streamlit (for deployment)

## Key Features
* **Data Integration:** Cleaned and merged disparate datasets using a custom key.
* **Exploratory Data Analysis (EDA):** Identified demand spikes during rush hours and their correlation with weather.
* **Predictive Modeling:** Implemented a pipeline with `ColumnTransformer` and `GridSearchCV` for hyperparameter tuning.

## Live Demo
Check out the interactive prediction tool here: [🚀 View Live App](YOUR_STREAMLIT_LINK_HERE)

## How to Run Locally
1. Clone the repository:
   `git clone https://github.com/EshaHundekarCdac/Cab-Surge-Price-Predictor.git`
2. Install dependencies:
   `pip install -r requirements.txt`
3. Run the notebook `cab_surge_predictor.ipynb` or launch the app:
   `streamlit run app.py`

---
*Created as a project to demonstrate end-to-end Machine Learning lifecycles.*
