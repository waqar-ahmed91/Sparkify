<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Business Requirements](#business-requirements)
* [Data Preparation](#data-preparation)
* [Results](#results)
* [Repository Files](#repository-files)
* [Contact](#contact)


<!-- ABOUT THE PROJECT -->
## About The Project
This project is all about analyzing and predicting the churn rate of the users from the data provided by a fictional music streaming company called 'Sparkify'. Users used this platform as a free member and paid member. While using the service data is generated in terms of playing a song, visiting a page etc.. According to the company some users downgraded their services from paid to free and some leave the services after using it for some time. So the main purpose of this project is to design a model that can predict the churn rate of the users according to the data provided.
<!-- Built With -->
### Built With
This project is built with Jupyter Notebook using Pandas, Numpy, Matplotlib, Seaborn, PySpark.
<!-- Business Requirements -->
## Business Requirements
The business requirement is to predict the churn rate of the new users by training and using machine learning models with a high f1-score.
<!-- Data Preparation -->
## Data Preparation
The dataset was messy and most of the datatypes are incorrect as well as some of the data are missing so thorough data wrangling process is used to clean the data as much as possible to make the data consistent and suitable for analysis and fulfilling the above mentioned business requirements.
## Results
The f1-score for the both tuned models Logistic Regression and Random Forest Classifier was same approximately 65.5% which needs to be enhanced using some different approaches like further fine tuning the models or using different models like SVC, NaiveBayes, XGBoost etc..

## Repository Files
- Sparkify.ipynb # Main Jupyter Notebook
- Sparkify.html # HTML file of Main Notebook
- Sparkify - User Churn Prediction Blog.html # Blog about user churn prediction
- Sparkify - User Churn Prediction Blog.ipynb # Blog Notebook
- README.md # README file to briefly describe the project.
<!-- CONTACT -->
## Contact

Waqar Ahmed - waqar.nu@gmail.com

Blog Link: [https://waqar-ahmed91.github.io/](https://waqar-ahmed91.github.io/)

Project Link: [https://github.com/waqar-ahmed91/Sparkify](https://github.com/waqar-ahmed91/Sparkify)
