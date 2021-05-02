# Property Price Prediction

<!-- Add buttons here -->
[![Open in Colab](https://img.shields.io/badge/-Open%20in%20Colab-e8710a?logo=google-colab)](https://colab.research.google.com/github/dewith/property_prices)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-black)](https://www.python.org/)
![Status](https://img.shields.io/badge/Project%20status-Completed-black)
![Last commit](https://img.shields.io/github/last-commit/dewith/property_prices?color=black)
![License](https://img.shields.io/github/license/dewith/property_prices?color=black)


<!-- End buttons here -->


This project's aim is to predict the prices of properties (located in Buenos Aires) published in [**Properati**](https://properati.com/).

<details>
<summary>Table of content</summary>

- [Project description](#project-description)
    - [Methods used](#methods-used)
    - [Technologies](#technologies)
- [Results](#results)
- [Next steps](#next-steps)
- [Contact](#contact)

</details>

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

# Results :dart:
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
