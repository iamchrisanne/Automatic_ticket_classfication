# Automatic_ticket_classfication
In this case study, you will create a model that can automatically classify customer complaints based on the products and services that the ticket mentions.
# Problem Statement
You need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

Credit card / Prepaid card

Bank account services

Theft/Dispute reporting

Mortgages/loans

Others

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.
# Expected tasks
You need to perform the following eight major tasks to complete the assignment:

Data loading

Text preprocessing

Exploratory data analysis (EDA)

Feature extraction

Topic modelling 

Model building using supervised learning

Model training and evaluation

Model inference

 

Note: Once you have finalised the clusters/categories for customer complaints, the next step is to create a data set that contains the complaints and labels (which you found using NMF). This labelled data set will be used for model building using supervised learning. 

You need to try at least any three models from logistic regression, naive Bayes, decision tree and random forest. 

You need to select the model that performs the best according to the evaluation metrics.
