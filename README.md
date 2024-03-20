# **Customer Churn Prediction**

## About the Project

Welcome to our Customer Churn Prediction project! In this end-to-end project, I've built a robust customer churn prediction model that enables businesses to anticipate and mitigate customer churn effectively. Project covers everything from data collection to model deployment.

Key features:
- Comprehensive data analysis and preprocessing
- Machine learning model training for customer churn prediction
- MLOps integration for seamless model deployment
- Insights and recommendations for customer retention strategies

## Prerequisite:

- An IDE/ Text Editor 
- Python 3.11.1 
- pip (or Anaconda)
- An environment management tool such as virtualenv, pipenv, venv, virtualend, conda.

    ### Python virtual environment set-up 
    - Method
    - -----------------------------
    - python -m virtualenv --version
    - virtualenv --version
    - virtualenv venv
    - .\venv\scripts\activate   
    - pip --version
    - python --version
    - pip install jupyterlab
    - python -m pip install --upgrade pip
    - pip --version
    - Deactivate when needed
      - .\venv\scripts\deactivate

    - Run JupyterLab 
    - jupyter lab

## Installation

To set up this project on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/sunone5/telco_churn.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Run Jupyter notebook
 - Run "Jupyter lab" and load the "./../notebook/EDA.ipynb for entire data analysis & model development.

## Run Streamlit App for Online and Batch prediction
- streamlit run app.py --server.port 5998

* Specify the port {--server.port} when ports are blocking by firewall app.

![Alt Text](streamlit-app.gif)
