Hey! I'm Haris Hasan and here's a select collection of my academic and hobby data science projects.
<br> Check me out on LinkedIn [here](http://www.linkedin.com/in/harishasan001) and reach out at hasan35@purdue.edu!

(Clicking on the headings will take you to the code / presentation)

______

### Table of Contents:
- [Can we predict NYC taxi cab fares?](https://github.com/harishasan001/data-sci-portfolio#-can-we-predict-nyc-taxi-cab-fares)
- [Can we use meeting notes to identify the best clients?](https://github.com/harishasan001/data-sci-portfolio#-can-we-use-unstructured-meeting-notes-to-identify-the-best-potential-clients) 
- [Can we use COVID-19 survey data to identify good investments?](https://github.com/harishasan001/data-sci-portfolio#-how-can-we-use-covid-19-survey-data-to-identify-good-investments)
- [Crypto Stock Crash EDA](https://github.com/harishasan001/data-sci-portfolio#-crypto-stock-crash-eda)
- [Psych Research](https://github.com/harishasan001/data-sci-portfolio#-psych-research) 

______


## [🚕 Can we predict NYC taxi cab fares?](https://github.com/harishasan001/data-sci-portfolio/blob/main/NYC%20Taxi%20Fare%20Prediction.ipynb)
#### End-to-End ML model: Data Cleaning, Exploratory Data Analysis, Supervised Linear Regression Model
I wrote out a fully detailed report of my methods and learnings [here](https://github.com/harishasan001/data-sci-portfolio/blob/main/NYC%20Taxi%20Fare%20Prediction%20Report%20%2B%20Explanation.pdf) where I explain my thoughts alongside the code. It's quite long so here are some screenshots that should serve well as a TL;DR:

***Context***
<p><img src="NYC Taxi Fare Report intro.PNG" width="487.2" height="280.8"></p>  

***An example of my reasoning and methods***
<p><img src="NYC Taxi Fare exploring.PNG" width="487.2" height="280.8"></p>

***Results***
<p><img src="NYC Taxi Fare outcome.PNG" width=""600 height="90"></p>


## [📔 Can we use meeting notes to identify the best clients?](https://github.com/harishasan001/data-sci-portfolio/blob/main/Meeting%20Notes%20Project%20_%20Haris%20Hasan.pdf) 
#### Data Analysis, Sentiment Analysis, Opinion Mining

Here we manually went through 800 comments from meeting notes over about 8 weeks, where each comment was
rated on a scale of 1-5 in 5 different categories (with one of the categories just being a confidence
rating)

Then, we used Microsoft Azure to look consider the sentiment analysis and key phrases, and compare the results with what we found in our manual analysis.
Azure’s analysis tended to have more positive and negative sentiments, whereas in our manual analysis we gave more mixed sentiments. Also, we found that Azure identified more key phrases that we did not identify in our analysis, but some of these words may or may not be useful depending on the context that they are used in the comment.

Finally, we used the sales data to determine the correlation between the sales and dimension scores, and found the correlation coefficient for each of the five categories to reach our conclusions.

***An example of some of my analysis***
<p>
  <img src="Meeting Notes Project 1.PNG"><img src="Meeting Notes Project 2.PNG"><img src="Meeting Notes 3.PNG">
</p>


***Results***
We realized that Account Penetration was perhaps the most important Dimension Score because it demonstrated the greatest Correlation Coefficient

Practically this means that High Penetration phrases such as “Met with Dr, met with doc”, “Met with office manager”, “met with OM”, “Interested”, etc. can lead to greater Total Sales in the past, present and future.

## [😷 How can we use COVID-19 survey data to identify good investments?](https://github.com/harishasan001/data-sci-portfolio/blob/main/COVID-19%20Data%20Investment%20Project%20_%20Haris%20Hasan.pdf)
Justified a novel hypothesis for investment into artificial-intelligence-based hiring technologies with a focus on rehiring opportunities using COVID-19 survey data using Microsoft Azure 
Achieved highest grade standard for analysis work and presentation

## [📉 Crypto Stock Crash EDA](https://github.com/harishasan001/data-sci-portfolio/blob/main/Crypto%20Stock%20Crash%20Exploratory%20Data%20Analysis.ipynb) 


## [🧠 Psych Research](https://github.com/harishasan001/data-sci-portfolio/blob/main/Psych%20Research%20.ipynb) 

Created a dynamic database framework of 100,000+ data points using Python to enable future analysis tasks
