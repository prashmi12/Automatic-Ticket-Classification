# Case Study : Automatic Ticket Classification
> build a model that is able to classify customer complaints based on the products/services using non-negative matrix factorization (NMF)

## Table of Contents
* [General Info](#general-information)
* [Libraries Used in Python](#libraries-used)
* [Acknowledgements](#acknowledgements) 

## General Information <a name="general-information"></a>
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.  

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, we will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans.

**Goal:**
We need to build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, we will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, we will be able to identify the topics of the customer complaints.  

We will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, we need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

With the help of topic modelling, we will be able to map each ticket onto its respective department/category. We can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.

**We are going to solve the problem in following sections i.e. :**
- Data loading
- Text preprocessing
- Exploratory data analysis (EDA)
- Feature extraction
- Topic modelling
- Model building using supervised learning
- Model training and evaluation
- Model inference

## Libraries Used in Python <a name="libraries-used"></a>
- numpy 
- pandas
- sklearn
- nltk
- wordcloud
- swifter
- plotly
- matplotlib.pyplot
- en_core_web_sm

## Acknowledgements <a name="acknowledgements"></a>
- This project is given by Upgrad as an assignment case study
- All the data and requirements are provided by Upgrad.
