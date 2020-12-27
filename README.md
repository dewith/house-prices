<!-- Add banner here -->
![Banner](/images/header.png)

# House Prices Prediction 🏡

<!-- Add buttons here 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dewith/house-prices.git/HEAD?filepath=P2_properati.ipynb)
![GitHub last commit](https://img.shields.io/github/last-commit/dewith/house-prices)
![GitHub](https://img.shields.io/github/license/dewith/house-prices)
-->


[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](
https://deepnote.com/launch?template=deepnote&url=https%3A%2F%2Fgithub.com%2Fdewith%2Fhouse-prices%2Fblob%2Fmain%2FP2_properati.ipynb)

This project's aim is to predict the prices of properties (located in Buenos Aires) published in [**Properati**](https://properati.com/).

**-> Project status:** [ Completed ]

<br>

## Table of contents
- [Table of contents](#table-of-contents)
- [Project description](#project-description)
    - [Methods used](#methods-used)
    - [Technologies](#technologies)
- [Results](#results)
- [Next steps](#next-steps)
- [Contact](#contact)

<br>

# Project description
[(Back to top)](#table-of-contents)

The company's property appraisers do the valuation in the traditional way, this means that the process is subjective to the appraiser's criteria.
 
Currently the process is slow, and there is a risk of under- or over-valuing a property. This in turn generates customer dissatisfaction. 

**Objective:** Create a model based on advanced Machine Learning techniques to predict property prices based on their attributes.

## Methods used
* Descriptive statistics
* Data visualization
* Feature engineering 
* Machine learning

## Technologies 
* Python
* Numpy, Pandas, Scipy 
* Matplotlib, Seaborn 
* Scikit Learn
* XGBoost

<br>

# Results
[(Back to top)](#table-of-contents)

In the project I studied in detail the predictor variables and their relationships with the target variable. Based on the exploratory analysis I found that the variables that best predict the price of a property are the surface area_covered and the number of bathrooms. An average error of 49k USD was achieved with the best model (XGBoost), which is equivalent to 16.8% average error.

![Results](/images/xgb_evaluation.png)

<br>

# Next steps
[(Back to top)](#table-of-contents)

To improve the performance of the model the following steps could be taken (ordered by ascending complexity): 
1. Only work with data from one city when training a model, this reduces variability and therefore decreases error 
2. Add the neighborhood variable in the training (this will increase the computer cost but can generate a non-spectacular but considerable gain) 
3. Create a model by type of property: one for apartments and another for houses, because although both are habitable properties they have very different behaviors. In this way you can focus actions to reduce the error independently. 
4. Complement the dataset with more specific data on the property's environment, such as the crime rate by area, socioeconomic status, and the number of businesses in the vicinity, among others. 
5. Work with geolocation data combined with an API map to obtain the number of stores and areas of interest around automatically, as well as prices of nearby houses.

<br>


# Contact
[(Back to top)](#table-of-contents)

You can visit my [**Personal Website**](https://dewith.co/), follow me on [**Twitter**](https://twitter.com/DewithMiramon/), connect with me on [**LinkedIn**](https://linkedin.com/in/dewithm/), or check out the rest of my projects on my [**GitHub**](https://github.com/dewith/).

<br>
<br>

![Footer](/images/footer.png)
