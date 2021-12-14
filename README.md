# Udemy-ML-1st-Project
This is my answer to the first project of the "20+ End-To-End Machine Learning Projects &amp; Deployment 2021" course (section 11).

The more detailed description of the project is as follow:

## Data Description:

The data is related to the direct marketing campaigns of a Portuguese banking institution.
The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (‘yes’) or not (‘no’) subscribed.

Domain:

Banking

Context:
Leveraging customer information is paramount for most businesses. In the case of a bank, attributes of customers like the ones mentioned below can be crucial in strategizing a marketing campaign when launching a new product.

Attribute Information:
age (numeric)

job : type of job (categorical: ‘admin.’,’bluecollar’,’entrepreneur’,’housemaid’,’management’,’retired’,’selfemployed’,’services’,’student’,’technician’,’unemployed’,’unknown’)

marital : marital status (categorical: ‘divorced’,’married’,’single’,’unknown’;
note: ‘divorced’ means divorced or widowed)

education (categorical:
‘basic.4y’,’basic.6y’,’basic.9y’,’high.school’,’illiterate’,’professional.course’,’univers
ity.degree’,’unknown’)

default: has credit in default? (categorical: ‘no’,’yes’,’unknown’)

balance: average yearly balance, in euros (numeric)

housing: has housing loan? (categorical: ‘no’,’yes’,’unknown’)

loan: has personal loan? (categorical: ‘no’,’yes’,’unknown’)

contact: contact communication type (categorical: ‘cellular’,’telephone’)

day: last contact day of the month (numeric 1 -31)

month: last contact month of year (categorical: ‘jan’, ‘feb’, ‘mar’, …, ‘nov’, ‘dec’)

duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y=’no’). Yet,
the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

previous: number of contacts performed before this campaign and for this client (numeric)

poutcome: outcome of the previous marketing campaign (categorical:
‘failure’,’nonexistent’,’success’)

target: has the client subscribed a term deposit? (binary: “yes”,”no”)

Learning Outcomes:
Exploratory Data Analysis

Preparing the data to train a mode

Training and making predictions using an Ensemble Model

Tuning an Ensemble model

Objective:
The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

Steps and tasks:
Import the necessary libraries (2.5 marks)

Read the data as a data frame (2.5 marks)

Perform basic EDA which should include the following and print out your insights at every step. (15 marks)

The shape of the data (2 marks)

The data type of each attribute (2 marks)

Checking the presence of missing values (4 marks)

Point summary of numerical attributes (3 marks)

Checking the presence of outliers (4 marks)

Prepare the data to train a model – check if data types are appropriate, get rid of the missing values etc. (15 marks)

Train a few standard classification algorithms, note, and comment on their performances across different classification metrics. (15 marks)

Build the ensemble models and compare the results with the base models. Note Random forest can be used only with Decision trees. (15 marks)

Compare performances of all the models (5 marks)

Based on the given data, will a customer subscribe to a term deposit or not?

Apply the concepts and techniques you have learned in the previous weeks and summarise your insights at the end.

Submission
Submit your answer in two ways.

1. Push your solution to your Github repository, and share the link on WhatsApp: +919467891831 for verification and marks

2. Write a summary explanation of your process in building your Linear Regression model in the form of an article in your personal publication.



Join Telegram Channel for any queries: https://t.me/tdsnow

NB: If you don’t have a publication yet, watch the ” Set Up Your Personal Publication/Blog” to set it up.

Good luck

Questions for this assignment


Based on the given data, will a customer subscribe to a term deposit or not?
