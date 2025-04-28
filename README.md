# fit3152-tutorial-06-regression-solved
**TO GET THIS SOLUTION VISIT:** [FIT3152 Tutorial 06-Regression Solved](https://www.ankitcodinghub.com/product/fit3152-data-analytics-tutorial-06-regression-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119403&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FIT3152 Tutorial 06-Regression Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Pre-tutorial Activity

The dataset “mpg” from the ggplot2 package contains fuel economy data for popular car models released between 1999 and 2008. City and highway fuel consumption in miles per gallon are given under the two variables “cty” and “hwy”. Nine other variables provide insight on the type and features of each car.

1. Fit separate linear regression models to predict city and highway fuel consumption based on the type and features of each car.

2. Which three variables are the most significant predictors in each model? Are they the same in each case?

3. How good are the two models comparatively?

Tutorial Activities

1. The ‘diamonds’ data set comes packaged with ggplot2 and contains data about the price of diamonds as well as information on size as well as the 4 Cs affecting diamond price: carat (size), cut, colour and clarity.

(a) Taking a random sample using the code below, create a subset of the diamonds data set: ‘dsmall’ to use in the following analysis.

install.packages(“ggplot2”) library(ggplot2)

set.seed(9999) # Random seed to make subset reproducible

dsmall &lt;- diamonds[sample(nrow(diamonds), 1000), ] # sample of 1000 rows

(b) Using the data ‘dsmall’ calculate the regression of ln(price) on ln(carat) and each of the remaining categories (clarity, color and cut) separately. Which of, clarity, color or cut has the greatest effect on price? Which has the least? Justify your answer using regression output.

2. The file “body.dat.csv” contains data from a study on the relationship between body dimensions. The study measured 500+ active individuals.

The data was obtained from http://www.amstat.org/publications/jse/jse_data_archive.htm A related article is http://www.amstat.org/publications/jse/v11n2/datasets.heinz.html

(a) Test the hypothesis that men are taller than women on average. Assume a significance of 5%

(b) Test the hypothesis that men are heavier than women on average. Assume a

significance of 1%

1

!”#$

(c) BMI is calculated as !. Test the hypothesis that men have a higher BMI

+%”#$%&amp; (,)-

than women on average

(d) Calculate the regression of Height on the other body measurements for men and women separately. Which measurements are the most significant predictors of height for each gender?

Calculate the regression of Spend vs Delta for each customer and summarize the results in a data frame similar to that below. Hint: try using “plyr” package and dlply function.

CustomerID RegIntercept RegSlope

4. Using the data from the UCI Machine Learning Repository comment on the factors affecting red wine quality. Data site is: http://archive.ics.uci.edu/ml/datasets/Wine+Quality The file name is: winequality-red.csv.

5. Install the “ISLR” library. Using the “Carseats” data, calculate the regression equation predicting Sales (child car seat sales) as a function of the input variables. Which variables are significant predictors?

6. The text, G. James et al., An Introduction to Statistical Learning: with Applications in R (ISLR) uses the “Advertising” data set to illustrate a number of different learning models. A description of the data (p15) follows: “The Advertising data set consists of the sales of that product in 200 different markets, along with advertising budgets for the product in each of those markets for three different media: TV, radio, and newspaper. A copy of the data was downloaded from: https://www.kaggle.com/ashydv/advertising-dataset and is on Moodle.

Using the Advertising data, answer the following questions (taken from pp59-60 ISLR):

(a) Is there a relationship between advertising budget and sales?

(b) How strong is this relationship?

(c) Is the relationship linear?

(d) Which media contribute to sales?

(e) How accurately can we estimate the effect of each medium on sales?

(f) (Extension) Is there synergy (interactions) among the advertising media?

Potential ways of addressing these questions using regression models and extensive discussion of regression can be found on pages 59-82 of ISLR.

2
