NewYork Price-Prediction App
This repository contains the deployment files and notebooks for the a machine learning price predictor that was deployed using heroku and flask.

Contents
app.py: The main application file for the project.
Dataset: A directory containing the project's datasets.
nyc-rolling-sales.csv: The original dataset file.
nyc-rolling-sales_new_cleaned_data.csv: The cleaned version of the dataset.
models: Directory containing the trained machine learning model.
model_filename1.pkl: The trained model in pickle format.
Procfile: Used for deploying the application on Heroku.
requirements.txt: Lists the required Python packages for the project.
runtime.txt: Specifies the Python version to be used.
templates: Directory containing HTML templates for the web application.
index.html: Main HTML template file.
new_modified_index.html: Modified version of the main template.
Ugoeze Project Code (EDA and model building).ipynb: Jupyter notebook detailing the exploratory data analysis and model building process.
Ugoeze Project code 1 (Data Cleaning).ipynb: Jupyter notebook detailing the data cleaning process.
Setup and Installation
Clone the repository.
Install the required packages using pip install -r requirements.txt.
Run the application using python app.py.
Deployment
This project is ready for deployment on Heroku. Ensure you have the Heroku CLI installed and set up. Deploy using the Procfile provided.

Contributing
Feel free to fork this repository, make changes, and submit pull requests. Feedback is always welcome.
