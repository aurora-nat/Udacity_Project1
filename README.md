# Udacity_Project1
This is a repository for my first project of Udacity's Machine Learning Course

## Project One Objective
The objective of **Project One** was to build a multiple Linear Regression Model utilizing the standard data mining process called CRISP-DM. CRISP-DM stands for Cross Industry Standard Process for Data Mining, and it will describe the life cycle of a data science project. 

CRISP-DM invovles 6 iterative steps which are the following:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Data Presentation or Deployment

The project will review each of the steps carefully utilizing Insider Airbnb's Clark County, NV Data to review how a normal data science project would follow CRISP-DM. In the end of the project, I build a linear regression model to predict the price of a listing.

## Summary Of Project Results:
The goal was to understand what features within Insider's Airbnb Data contributed to the price of a listing. We explored the data using the CRISP-DM methodology and unconvered that utilzing the following features: accommodates, price, review_score_rating, reviews_per_month, amenities, and room type led to a good prediction estimate using our linear regression model. Further iterations of the CRISP-DM project can lead to a better r-squared score in future developments.

## Installation
Clone the github repository and you will need to have Jupyter Notebook Installed with proper libraries for the code to run.

For beginners here are all the libraries you will ned to install before being about to run the jupyter notebook.

If you do not have pip installed you will have to first install pip, instructions are for Mac/OS.

## Install pip
```
python get-pip.py
```

## Install Jupyter Notebook using Pip
```
pip install notebook
```
## Install numpy
```
pip install numpy
```

## Install pandas
```
pip install pandas
```

## Install matplotlib
```
python -m pip install -U matplotlib
```

## Install sklearn
```
pip install sklearn
```
## Instal seaborn
``` 
python -m pip install seaborn
```

Once you have installed the above libraries, you will have to include into your directory the .csv file that was used.
Go to http://insideairbnb.com/get-the-data.html and located Clark County, NV and download the December 2020 file to the folder containing this repository. 


Once you have the files properly installed you will be able to run the jupyter notebook accordingly. 

If you would like to review my blog post for a walk-through of this project, feel free to check out this link:
https://nataly-nuila.medium.com/how-can-you-determine-your-price-for-you-airbnb-in-las-vegas-ca-661bcf917b1



