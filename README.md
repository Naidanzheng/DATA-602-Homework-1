# DATA-602-Homework-1
# Child's birth weight
#####    by Naidan Zheng


---

## Overview
The health scientists are challenging to find the relationship between cigarettes and child's birth weight. We used the data on births to women in the United States to see how cigarettes would affect child's birth weight, and what the determinations of child's birth weight are.


## Data
The data set bwght.csv contains data on births to women in the United States. Two variables of interest are the infant birth weight in ounces (bwght), and the average number of cigarettes the mother smoked per day during pregnancy (cigs).The data set includes 1,388 columns and 14 varialbes. The average birth weight of the baby when the mother is not a smoker is 119.77 ounces.

![bwght.png](https://github.com/Naidanzheng/DATA-602-Homework-1/blob/master/bwght.png)

## Model
Based on the question, I used the simple linear regression model: f(x)= beta0+beta1x. It is a statistical method that allows us to summarize and study relationships between two continuous (quantitative) variables:independent variable(x) and dependent variable(y).

![cigs.png](https://github.com/Naidanzheng/DATA-602-Homework-1/blob/master/cigs.png)

The line on the line graph moves from left to right, the line falls, which means the graph shows that cigarettes and birth weight have negative linear relationship.

After calculating the coefficient parameter, the simple linear regression model: bwght=120.2964-0.5758cigs, where n=1192,R^2=0.025.
Therfore, as more cigarettes are smoked, the birth weight of the baby decreases at the rate of 0.5758 ounce for every additional cigarette smoked per day.
