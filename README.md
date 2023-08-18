<div align="center">
  <img src="Roy Chen Logo.png" alt="Project Logo" width="200">
  <h1>🌟Data Science Project<br/>Portugal Investments & Real Estate🌟<br/> 🕵️‍♀️🕵️‍♂️</h1>
</div>

## Table of Contents
- [About Me](#About-Me)
- [The Research Question](#The-Research-Question)
- [Why](#Why)
- [Data](#Data)
- [ALGORITHMS](#ALGORITHMS)
- [TOOLS](#TOOLS)
- [CONCLUSIONS](#CONCLUSIONS)
- [License](#license)

## About Me
👨🏽‍💻 Roy Chen,
Second year Computer Science students at H.I.T.,
I really like Python, I have a passion for experimenting with new things and interesting technologies.
This is my final project in the machine learning course.

## The Research Question
📚 The goal of this project is to use classification models to identify properties that are good for investment. 

## Why
❓ ❔In recent years, Jews who could prove that they were
deported from Spain, could submit an application to
the Portuguese authorities and the Jewish community
living in Porto or Lisbon, and ask for citizenship in
Portugal only by proving that they are descendants of
those deported from Spain

🔍 At the end of 2022, the Portuguese government
decided to tighten the conditions for obtaining
citizenship and a Portuguese passport for the
descendants of those deported from Spain, and from
now on you also have to show affinity to the state of
Portugal
One of these ways is to invest or purchase real estate in
Portugal.

We decided to check whether it is possible to analyze
the information on properties in Portugal using the
Remax Portugal website, and to determine what is a
good property for investment in Portugal

The goal is to help those Jews who want to become
citizens in Portugal and are now faced with the
tightening of the conditions for obtaining citizenship

## Data
📊 The Data we scrapped from https://www.remax.pt/en/
before handling and cleanning we gained 11665 properties for buy
and 1452 properties to rent.


## ALGORITHMS
🛅At first we built a linear regression equation to predict rents for rental properties.

the model we achieved
We operated on properties to buy.

We calculated the monthly profits on the property that the property owner receives from rent, and subtracted the monthly expenses that the property owner loses,
which is the mortgage and current monthly expenses such as taxes, insurance and the like.

After data preparation and EDA, we built a base of machine learning and classification models.


## TOOLS
🛠<br/>
•Selenium<br/>
•Beautiful Soup <br/>
•Pandas<br/>
•matplotlib <br/>
•Regression<br/>
•classification<br/>
•sklearn.  <br/>

## CONCLUSIONS

👨🏽‍🏫It can be observed that the accuracy results were
XGBoost 0.688
SVM 0.697
Gaussian NB 0.651
Dec Tree 0.665
Random Forest 0.683
KNN 0.671
LR 0.683
We saw the best model we checked was the SVM 
with the 0.697 accuracy.

## License
📝 This project is licensed under the Roy Chen License. See the [LICENSE](LICENSE) file for details.
