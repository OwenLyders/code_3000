# code_3000
Collection of Assignments for CSE 3000: Contemporary Issues in Computer Science and Engineering

_Note_: Odd-numbered assignments are in HuskyCT, while even-numbered assignments are found in this repo and can be submitted to Gradescope via a Github connection.

## Outline of Assignments

### Module 02: Bot Predictor
Your goal is to build a machine learning model using given data and a Python template. You'll make changes to the GradientBoostingClassifer in mod02_build_bot_predictor.py and then test your changes in mod02_test_bot_predictor.ipynb. Can you minimize the misclassification rate on the test set?

### Module 04: Model Bias
You are given a model that was built to predict a mystery variable using zip code, income, and education level. The variable "group" represents a demographic that is prohibited and was NOT used in the model. Your goal is to use the SHAP package to review this model for bias.

### Module 06: Data De-Anonymization
Your goal is to connect anonymized data back to its source data and check the match rate. To complete this activity, write functions in the "deanonymize" script to (1) link the records in the two datasets and (2) calculate the rate at which you are successful doing so. 

### Module 08: Sustainability in Computing
You will be given a toy dataset and have the opportunity to explore the potential effects of choosing sustainable energy sources to perform computations. You'll code the energy calculation in "sustainability calculations" script, and then you can review the results of various decisions in the "check calculations" notebook. 

## Personal Ethics Statement

My main takeaway from Chapter 5 of *Ethical Machines* is that an ethics statement only matters if it changes what someone actually does. Saying "I value fairness and privacy" is easy, but it doesn't tell me what to do when a deadline or a good result pushes the other way. So these are the commitments I want to hold myself to as an engineer:

- **Fairness:** I will test a model for bias before I trust its results, even when a protected attribute isn't one of its inputs, because other variables can stand in for it.
- **Privacy:** I will not treat data as safe just because the names were removed. In Module 06, I re-identified 42.1% of "anonymized" records using only age, gender, and a 3-digit ZIP code.
- **Honesty:** I will tell people what a system can't do and what its known risks are, even when that makes the project look worse.
- **Speaking up:** If I believe something I'm working on could seriously harm people, I will raise it and refuse to ship it quietly.

I care about these because the people affected by software usually have no say in how it gets built, so the people building it have to think about them.
