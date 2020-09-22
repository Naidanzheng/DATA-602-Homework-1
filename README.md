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
Therefore, as more cigarettes are smoked, the birth weight of the baby decreases at the rate of 0.5758 ounce for every additional cigarette smoked per day.

To diagnose a linear model.
![predicted.png](https://github.com/Naidanzheng/DATA-602-Homework-1/blob/master/predicted.png)

From the graph, the residual plot is a good model when it only used to find the relationship between birth weight and cigarettes.

To find the other determinations of child's birth weight rate. 
![coefficient.png](https://github.com/Naidanzheng/DATA-602-Homework-1/blob/master/coefficient.png)

The graph shows the correlation between features.          
The simple regression from question 1 does not complete explain the causal relationship, because it doesn't analyze other factors which might affect child's birth weight. Child's birth weights affects by the factors such as family income, birth order of the child, race, gender, and parent's education.
Therefore, it is more accurate to predict child's birth weights by using these factors.
The multiple linear regression model: bwght=-377.4788+-2.033e+6cigs+103.7763lbwght+  ... + 4.065e+07packs + 0.0078cigprice,n=1192, R^2=0.954.
This model is more accurate than the simple linear regression model.


## Conclusion
Mother smoking definitely affects child's birth weight, but it is not the only factor. It is necessary to consider more determinations which will help us to get more accurate data. The multiple linear regression model will help health scientists to analyze child's birth weight, 

## Future
To get more accurate results, we'd like to have more addtional data, such as the effect of father smoking on children, mother's weight and mother's height.

---

## Resource
bwght.cvs
- [website](https://www.stata.com/texts/eacsap/)
