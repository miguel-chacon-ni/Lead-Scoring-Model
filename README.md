[Repository](https://github.com/miguel-chacon-ni/Lead-Scoring-Model) <br>
[Presentation](https://github.com/miguel-chacon-ni/Lead-Scoring-Model/blob/main/Presentation.pptx)

# Scoring Banking Leads
*Miguel Chacón*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Analysis](#analysis)
- [Cleaning](#cleaning)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Deliverables](#Deliverables)
- [Links](#links)

## Project Description
In this project, I use Machine Learning with Python to create a lead scoring model, leading a 50% increase in conversion rate. It is meant to show my understanding of:

1. Machine Learning concepts, pipelines and model building & tuning.
2. Digital Marketing and conversion rate optimization.
3. Python, Pandas, and Scikit-learn.
4. Modeling and forecasting of business processes.

## Business Question
The client, a commercial bank, wants to improve its sales without hiring more sales representatives. I use Business Analytics frameworks to approach the question and deliver a solution.

The lead scoring model I delivered reduces the proportion of leads that are contacted while simultaneously increasing the conversion rate. All else equal, this will allow further lead-generation campaigns to increase their lead volume, leading to an increase in revenue and, thus, profitability.

## Dataset
The dataset consists of 45,000 instances of phone calls made by sales representatives during a sales campaign.

## Analysis
* Overview the general steps you went through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Include charts to demonstrate the effect of your work.
* If you used Machine Learning in your final project, describe your feature selection process.

## Cleaning
1. Dimensionality reduction achieved by merging categories.
2. Columns with multicollinearity were dropped.
3. Categorical columns were encoded.
4. The target variable was changed to a numerical type.

## Model Training and Evaluation
1. Tested 46 combinations of 8 algorithms and 6 scalers with default settings to find the combination with the highest recall score.
2. Selected a Random Forest Classifier and tested 100 parameter combinations with a 3-fold cross-validation for each, optimizing for Recall. The resulting model had 65% higher score than the model with default settings. 
3. To evaluate the model, I took a random sample of 15 leads and made educated guesses on whether they would convert, comparing my results against the model. The model's predictions led to a 50% higher conversion rate.

## Deliverables
1. A Machine Learning model that allows new leads to be assigned a score between 1 and 10 based on their likelihood to convert to sales, allowing the sales team to prioritize these for calls.
2. A PPT presentation detailing the business question, the model as a solution, and the results.

## Links

[Repository](https://github.com/miguel-chacon-ni/Lead-Scoring-Model) <br>
[Presentation](https://github.com/miguel-chacon-ni/Lead-Scoring-Model/blob/main/Presentation.pptx)
