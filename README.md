# Applied Statistics Projects
This repository is a collection of my projects focused on applied statistics


Click on any files to open the project pdf!

<!---
Objective & Motivation: What you were trying to do, and why
Role: Make it clear if it is a personal Project or if you were part of a team. If personal give a sense of the effort (e.g. x hours / week outside of core curriculum) you put in; if part of a team clarify your responsibilities
Data: Detail the approximate dataset size and skew, how (e.g., software and techniques used) to store, extract and clean the data
Models: Specify models and statistical techniques used, as well as programming languages and libraries used to construct them (paying particular attention here to the requirements noted on the job posting - the more you can cover off keywords/asks for the role the better!)
Code: It is worth linking to your Github account to give the Hiring Manager the option to check out the code (plus it just makes it all the more credible that you’ve actually done the work!). A bonus option here is to also create a readme.md for the projects you’re featuring on your resume - this template is a good example
Results: Try whenever possible to demonstrate the outcome with numerical impact or significance (it pops off the resume more than a text-only sentence) and is an indicator of how impact-oriented (or not!) you are in your work
If you follow the above high-level and specific advice your Project work should start to work for you! -->

* ##  [Predicting Home Sales Prices Using Multiple Linear Regression Part 1](https://github.com/Rlegaspi562/Statistical-Projects/blob/main/Predicting%20Home%20Prices%20Using%20Multiple%20Linear%20Regression/Predicting%20Home%20Sales%20Prices%20Using%20Multiple%20Linear%20Regression%20Analysis%20Pt.%201.pdf)


Objective & Motivation: The city tax assessor is interested in predicting residential home sales prices in a midwestern city given a dataset of various characteristics of the home and surrounding property. The feautures we use to predict sales price of a home are number of bedrooms, bathrooms, and garage size. 

Role: Statistician

Data: Our dataset consists of 522 total transactions from home sales in a midwestern city during the year 2002.

Models and statistical techniques:  Used R as the main programming language to conduct statistical analysis and Rmarkdown to knit and export results into a PDF
- Model Estimation and Interpretation
  - Fitting a Multiple Linear Regression model
  - Adjusted R-Squared
- Prediction
  - 95% Confidence Interval
  - 95% Prediction Interval
- Hypothesis Testing
  - T-test for partial slope significance
  - F-Test for Overall model significance
  - Partial F-Test to assess reduced and full model significance
- Multicolinearity
  - Scatterplots
  - Correlation Matrices

* ##  [Predicting Home Sales Prices Using Multiple Linear Regression Part 2](https://github.com/Rlegaspi562/Statistical-Projects/blob/main/Predicting%20Home%20Prices%20Using%20Multiple%20Linear%20Regression/Predicting%20Home%20Sales%20Prices%20Using%20Multiple%20Linear%20Regression%20Analysis%20Pt.%202.pdf)

Objective & Motivation: We continue our project of predicting residential home sales prices using the same dataset but now using different given features/explanatory variables: area of residence in square feet, and the absence or presence of a swimming pool or air conditioning in the home property. 

Additional models and statistical techniques: We continue the choice of R as our main statistical programming tool
- Regression using a Dummy Variable
  - hypothesis test on the significance of slope coefficient
- Fitting a Multiple Linear Regression model with Interaction Term of a Dummy Variable and Continuous Variable 
  - Plotting Fitted Regression Lines Between Dummy Variables
  - Testing for Parallel Lines Between Two Regression Lines
- Fitting into a regression only with Interaction of Dummy Variables
  - Caluclating estimated mean sales prices for 4 kinds of properties

### Results:
Based on our two-sided hypothesis test, we concluded that the slope coefficient was in fact significant. This tells us that a significant difference between the mean change in the sales prices comparing properties containing a swimming pool in reference to one without a swimming pool does in fact exist. 

In the second part of our analytical study, a multi-linear regression model that contains the interaction term of the dummy variable and the continuous variable was created. The goal of this was to establish whether the different linear regression models that resulted when the home contained a pool or did not contain a pool. We also looked at the effect that this would have dependent on the square footage of the property. The model revealed that our regression lines are not parallel, and a relationship exists between the two lines.

Based on our regression analysis it is clear that a property with a swimming pool and air conditioning ($356,752.3), cost significantly more than a property without 
($189,578.2.).

### Looking Forward:
For future reference we understand that our dataset is unbalanced with only about 7%, or 36 out of 522 observations owning swimming pools and 16%, or 88 out of 522 observations having air conditioning. Moving forward one way to correct this would be to collect more data from houses containing these features. Also, since the Interaction term between owning a swimming pool and having air conditioning is not significant and therefore remove this from the model.

* ##  [Regression Analysis of Infection Risk and Length of Stay](https://github.com/Rlegaspi562/Statistical-Projects/blob/main/Regression%20Analysis%20of%20Infection%20Risk%20and%20Length%20of%20Stay/Regression%20Analysis%20of%20Infection%20Risk%20and%20Length%20of%20Stay.pdf)
