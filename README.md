# Statistical-Reasoning-2
Seaside Chat Feb 9

## Learning Outcomes
1. Choosing the best statistical test for their data
2. Assess the number of variables, whether their data is discrete or continuous, quantitative or qualitative
3. Learn about the various assumptions that come with certain statistical tests
4. Gain a better understanding of common statistical tests

## Why We Chose This Topic
The world is filled with many different types of data. The variables in the data we collect can be continuous (i.e. body mass of penguins), discrete (i.e. number of years since forest fire), or categorical (i.e. red, green, or blue color in a fish species) Therefore it’s important to know which statistical tests are the most helpful to test your particular hypothesis and determine whether your predictor variables have statistically significant effects on an outcome. 

Let’s say you conducted an experiment or survey and collected a bunch of data. Every scientist in training has sat with a large dataset and felt unsure about which direction to take it. You did all your data cleaning and wrangling, and you hopefully have some question or hypothesis you want to address. Great! Now what? 

Knowing which statistical tests are available and when to apply them is a fundamental skill that scientists should practice. Whether you’re comparing means between two populations, or you want to determine if variance between your groups is different from the variance within each group, statistical reasoning helps you figure out what to do next.
 
Our goal is to provide an accessible blueprint for students to take the next step of their analysis and answer the question: what statistical test should I use to test my hypothesis?


## Key Information
Within the vast variety of statistical tests it is easy to get overwhelmed and become unsure of what to do. While there is no easy way to get to the perfect test, it is possible to narrow down those options by knowing the number and types of the variables you have. 

We will show a flow chart that helps to narrow down your options. Following it does not give a perfect solution but it will help find a helpful test, then it is up to you to find something potentially related to get you where you need.

Then we will show some of the most commonly seen statistical tests, when it is appropriate to use them, what they show, and what assumptions they make. 
The tests we will go through:
1. Regression tests
2. T-tests
3. ANOVA tests
4. Chi-squared tests

## Linear regression tests
Useful when modeling the relationship between response variable Y and predictor variable X.
Allow us to test for statistical relationships, how changes in predictor variable can influence the response variable

## Simple linear regression
One continuous predictor variable and one continuous response variable (assumes observations are independent, residuals are normally distributed)
Example: effect of sunlight exposure on plant growth

## Multiple linear regression
When to use: when you have two or more predictor variables for one response variable

What it does: estimates the independent effect of each predictor variable on the response variable while holding the other predictor variable constant. This allows us to test significance of multiple predictor variables simultaneously.
Example: effect of sunlight exposure and water availability on plant growth

## Logistic regression
When to use: When the response variable is categorical and binary (two possible outcomes), as opposed to continuous. Predictor variables can be continuous or categorical.

What it does: models probability that an outcome falls into one of two categories.

Assumptions: Response variable is binary. Observations are independent

Example: effect of nursing frequency on wolf cub survival (survived vs. not)

## Comparison tests: 
These are useful when you’re looking for the difference in means between two or more groups. 

## T-tests
When to use: comparing the means of exactly two groups. You have a discrete, independent variable with two levels and one continuous dependent variable.
(If you have three or more groups, consider a One-way ANOVA.)
Example: alarm playback experiment. Independent variable: playback exposure (before and after). Dependent variable: stress hormone concentration 

## Paired t-test:
When to use: whenever the same units are measured under two conditions, or if observations are naturally linked/matched. Used in before & after, or matched-pair study designs.
What it does: Compares the difference between the means of your two groups to determine whether that difference is statistically significant.
Assumptions: 
Differences between paired measurements are normally distributed
Each linked pair of measurements is independent of all other pairs
The dependent variable is continuous

Example: Stress hormone levels in individual birds measured before and after exposure to an alarm playback treatment.

## Independent t-test:
When to use: when comparing the means of two independent groups (each observation belongs to only one group)
What it does: Tests whether the difference between the means of two independent samples is statistically significant.
Assumptions: Observations are independent between groups. Data within each group are approximately normally distributed.The dependent variable is continuous

Example: Stress hormone levels in one bird species compared to levels in another bird species.


## One-way ANOVA:
When to use: If you have 3 or more groups. One discrete independent variable and one continuous dependent variable (if you have two discrete independent variables, consider a Two-way ANOVA).
What it does: Compares the difference between the means of three or more groups
Assumptions: The dependent variable values follow a normal distribution
		The variance in each group is the same/similar
		There are no confounding variables
For example: Comparing the amount of growth in plants where each plant got one of three watering treatments.

## Chi-Square:
	Assumptions: The expected values in most (ideally all) cells are greater than five.
Goodness of fit:
When to use: If you have one categorical variable with more than two groups. Usually done with a frequency table.
What it does: Compares the expected values to the observed values to determine statistical significance.	
For example: Test if the frequency of pollinators visiting certain flower colors is expected. (we expect that they will visit all colors with equal frequency)

## Test of independence:
When to use: If you have two categorical variables. Make sure to arrange them into a contingency table. 
What it does: Calculates an expected value based on (row total * column total) / grand total. Compares the expected values to the observed values to determine statistical significance
For example: Test if the frequency of visits to different flower colors based on pollinator family is expected.




## Final Outcomes
With this exercise, we aim to ensure students become more familiarzed with different statistical tests and how to pick the most correct test for their data type.

## Link To The Slides
https://docs.google.com/presentation/d/1MVwxlDDZ5rKMWrV_2qyHLCkIHj9_Fo2ux_HBW0BGthc/edit?usp=sharing
