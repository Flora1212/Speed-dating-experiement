# Speed-dating-experiement

The Speed Dating Experiment dataset from Kaggle(https://www.kaggle.com/annavictoria/speed-dating-experiment) using logistic regression analysis.

Introduction

The general goal for the study is to explore what attributes and characteristics influence the selection of a romantic partner, which can then be specified into four questions to answer: 
1. What are the most/least desirable attributes in a male partner? Does this differ for female partners? 2. How important do people think attractiveness is in potential mate selection vs. its real impact? 3. Are shared interests more important than a shared racial background? 4. Can people accurately predict their own perceived value in the dating market?

Materials and Methods

I conduct five steps in machine learning for our logistic regression analysis: Step 1 – Collecting data; Step 2 – Exploring and preparing data; Step 3 – Training a model on the data via the Holdout method; Step 4 – Evaluating model performance; Step 5 – Improving model performance.

The Speed Dating Experiment dataset originally contains 8378 observations and195 variables, with 4194 male and 4184 female participants. I select the decision variable, dec (Yes/No decision) after the speed dating event as the response variable. Since the response variable decision is a categorical binary variable with Yes=1 and No=0, I chose a logistic regression model for our analysis.

Then, I selected 14 variables most related to our stated research goals and with minimal missing data from the 195 variables as our independent variables. Specifically, the predictors are 6 attributes from the survey questions: attr (Attractiveness), sinc (Sincerity), intel (Intelligence), fun (Fun), amb (Ambition), shar (Shared Interests); 8 personal characteristics from other questionnaire information: Gender, samerace, imprelig, goal, age, date, go_out, exphappy. (details about the variables can be found in Kaggle)

