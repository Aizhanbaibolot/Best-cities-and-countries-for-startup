![image](https://user-images.githubusercontent.com/98500457/200929426-c36372b2-308b-41d0-b5bc-ea168a585372.png)

# **Statistical Analysis Startup Data**
### Project Overview <p>
The data is called The Best Cities and Countries for Startups. The dataset consists of 1000 records across 9 fields. I would like to answer two questions 
using the data. The first is to see if there is any correlation between quantity score and quality score of the countries. The second is to see if there
is a significant difference between total scores for cities with sign of change in position and without. I will use visualizations to show correlation,
and I will use t-test to test the significance of score differences for different cities with or without sign of change in position. Findings can be 
interesting for startupers as well as investors. The startupers will be interested in knowing which country or city to choose to realize their ideas. 
Also investors can use the findings to choose the correct location to invest their money and predict approximate scores.

### The Research Questions: 
There are two questions that will be addressed in this analysis:

* If there is any correlation between quantity score and quality score of the countries.
  
* If there is a significant difference between total scores for cities with sign of change in position and without.
  
### The Hypotheses
There are two hypotheses related to the previous research questions, as follows:
 
* Hypothesis 1: The country scores are correlated. This means that countries that scored well in one field are likely to score well in other fields.
  
* Hypothesis 2: There is no difference between the total scores of the cities with sign of change in position and without.
  
### How will the data test the hypotheses?

Visualizations will show a correlation between quality and quantity scores of the cities. Pearson r will test for correlation.  

T-test will show the significance of score differences for the cities with the sign of change in position and without. 

### Who will find the findings valuable, and how will they use them?

The startupers will be interested in knowing which country or city to choose to realize their ideas. 

Also, investors can use the findings to choose the correct location to invest their money and predict approximate scores.

## Analyses
  
### Hypothesis 1:

<img width="449" alt="image" src="https://user-images.githubusercontent.com/98500457/200925797-3049f621-0a50-45ab-8f30-fd582e536242.png">

* The scatterplot shows correlation between quantity and quality scores of the cities.
* Colors indicates if there is a sign of change in position or not.
* P-value is less than alpha(.05) Pearson r test
* There is a statistically significant linear relationship between quantity score and quality score of the countries. The relationship is positive.

### Hypothesis 2:

<img width="442" alt="image" src="https://user-images.githubusercontent.com/98500457/200926278-105a7fe0-a65f-41e0-961e-40c280c02ef7.png">

* The boxplot visually shows  the distributions between the cities with the sign of change in position and without the sign of change in position.
* An independent samples t-test was used to support the hypothesis 
* P-value = 0.13
* The t-test confirmed the hypothesis 2.

### Project Summary
* Hypothesis 1 has been rejected. There is a positive correlation between quality and quantity scores. Which means cities performing well in one field also perform well in the other one.
* Hypothesis 2 has been confirmed. There is no statistically significant difference in the average total score of the cities with the sign of change in position and without the sign of change in position.

## Recommendations
### Investors:
Look for quantity and quality scores of the cities when deciding to invest your money, since they indicate successfulness of the project you are investing in.
### Startupers:
Pick anywhere to start realizing your ideas regardless of the position of the countries. You can enter the market online which gives you wider audience and the location won't make any sense. 

### More Information
See the full analysis in the [Jupyter Notebook ](https://github.com/Aizhanbaibolot/Statistical-Analysis-Startup-Data/blob/main/capstone_3.ipynb) or review this [presentation](https://github.com/Aizhanbaibolot/Statistical-Analysis-Startup-Data/blob/main/capstone3_startups.pdf).

For additional info, contact Aizhan Baibolot at []()aizhanbaibolot0@gmail.com
