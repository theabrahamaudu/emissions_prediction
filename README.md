# Emissions Predction

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)


## About <a name = "about"></a>

This project was done to carry out Time Series prediction of green house gas emissions for different countries based on UN FAO data gotten from [Kaggle](https://www.kaggle.com/datasets/justin2028/total-emissions-per-country-2000-2020)

The model was built using multivariate approach by building a Vector Autoregressive Moving Average (VARMAX) model. To determine this approach as the best, the preprocessed data was tested for stationarity and causality. 

For full details on the preprocessing and model, kindly checkout the [EDA and Model Explainer](https://github.com/theabrahamaudu/emissions_prediction/blob/main/EDA%20and%20Model%20Explainer.docx)

## Getting Started <a name = "getting_started"></a>

To get started:
- Create a new virtual environment
- Clone this repository:
```
git clone https://github.com/theabrahamaudu/emissions_prediction.git
```
- Install dependencies
```
pip install -r requirements.txt
```

## Prerequisites

Python 3.x
  
  
## Usage <a name = "usage"></a>

- Navigate to the Emissions_Prediction.ipynb file
- Run all cells to ensure all modules are installed and helper functions are available
- Skip to the Demo Section and follow the instructions in the comments

The Demo is able to pick the name of the country you have chosen, and then based on the boolean value of the 'tune' parameter you have chosen, it will automatically make predictions either using a pretrained set of model parameters or using a new model based on the specific data for that country.  
__
###### * Setting "tune=True" will make the Demo runtime slower  
__  

To make forecasts
- Input the forecast start and end years and run the cell

### Author
[Abraham Audu](https://github.com/theabrahamaudu/) 

Socials  
[] [Twitter](https://twitter.com/the_abrahamaudu)  
[] [LinkedIn](https://www.linkedin.com/in/theabrahamaudu/)  


## Contributions and Observations
If you have any questions or contributions, please feel free to reach out to me.
Also, feel free to fork this repository and explore avenues to improve the code or approach. 