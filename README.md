# Tech_Salary_Prediction
 A web app to predict and visualize tech salary based on the country, experience and degree. The app is built using streamlit and deployed on heroku

# Data Science salary prediction

[![heroku deployed](https://raw.githubusercontent.com/DenisOH/pyheroku-badge/master/img/deployed-plastic.svg)](https://salary-prediction-st.herokuapp.com/)

This repository consists of files required to deploy a ___Machine Learning Web App___ for salary prediction created with ___Streamlit___ and deployed on ___Heroku___ platform.

The data are available from the 2021 stack overflow survey:
  [Download Full Data Set(CSV)](https://insights.stackoverflow.com/survey) 
   

In order to create the model the [pycaret](https://github.com/pycaret) library used with data for full time developers having income less than 250000 and greter than 10000. The application makes predictions using the following features (columns):

* Country
* Education Level
* Professional Level
* Years of experience


## Reproducing this web app 
To recreate this web app on your own computer without deployment on heroku, do the following.

### Create conda environment
Firstly, we will create a conda environment called *myenv*
```
conda create -n myenv python=3.7.11
```
Secondly, we will login to the *myenv* environement
```
conda activate myenv
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/quartermaine/Salary-prediction-deploy/main/requirements.txt
```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/quartermaine/Salary-prediction-deploy/archive/refs/heads/main.zip

###  Launch the app

```
streamlit run app.py
```

<br />
<br />
<br />

![pic](https://github.com/quartermaine/Salary-prediction-deploy/blob/main/readme_recources/salary_app.png)

<!-- ![pic](https://github.com/quartermaine/Salary-prediction-deploy/blob/main/readme_recources/salary_app.png) -->
