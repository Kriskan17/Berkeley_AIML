# Berkeley_AIML
Bank Marketing Campaign


# OVERVIEW
In this project, the goal is to predict deposit subscription by clients based on the previous marketing campaigns
# Dataset Information
Additional Information

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

There are four datasets: 
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs). 
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). 
The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM). 

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

# Business Understanding
We are given the data of direct marketing campaigns (phone calls) of a Portuguese banking institution. The goal is to predict if the client will subscribe a term deposit (target variable y). This case study is inspired by this research paper where the researchers have used a very similar dataset as the one we will be using throughout this case study for determining the success of Bank Telemarketing.

The following steps were taken to analyse the used car data
Data Understanding
Data Prep
Modelling
Evaluation


# Findings: The following are the important findings of this review : 

* Appropriate Timing: The timing of the marketing campaign during the year is important. The campaigns ran duing the months of March, August and May are more likely to enrol customers to the program.

* Economy : The external financial factors like High employment rate (emp.var.rate), Better CPI (Consumer price index ), euribor (3 month interest rate) are also important factors to consider.

* Duration and Previous Campaign : Duration of the call and Previous outcome may not be good indicators, as the duration of the call may just mean the people who enrolled actually spend more time to complete the enrollment process.

* The link to the colab notebook : https://github.com/Kriskan17/Berkeley_AIML/blob/main/practical_application_III/prompt_III.ipynb
  

