# Customer segmentation challenge for Analysts

Please complete the following data analysis challenge

### Description

Use the data provided in the file customer_data_sample.csv and, through the use of visualizations and statistics answer the questions:

- What are the most important factors for predicting, whether a customer has converted or not?
- Based on this, how would you construct the top 3 best audiences to test for marketing campaigns next?


### Definitions

Converted customer is represented in the data in the field "converted", and the nature of what this conversion means is (intentionally) unknown in the context of the challenge.

### Fields

The fields in the data are described below - the meaning of the values is encoded to numerical to enable you to focus just on the data, not on industry insights.

| field | explanation |
|---|---|
| customer_id | Numeric id for a customer
| converted | Whether a customer converted to the product (1) or not (0)
| customer_cohort | Numeric id of the cohort a customer belongs to
| gender | Customer gender identifier - this is obfuscated on purpose
| age | Customer age
| added_referrals | Numeric - number of people customer has referred the service to
| added_friends | Numeric - number of added friends
| plan_price | Initial plan price level the customer is enrolled to when they signed up
| source | Identifier (hash) for the customer acquisition source. Null values are represented with the hash  "9b2d5b4678781e53038e91ea5324530a03f27dc1d0e5f6c9bc9d493a23be9de0"
| country | Country the customer is from |

### Submission requirements

- Submit your answer as a version controlled repository (repo) in github or bitbucket
- Make sure your repo is public and submit a link to it via email
- Use summary statistics, visualization or other analytical means to explain your argumentation (showcase how you ended up in the conclusion you've reached)
- You can for example use ipython (jupyter) notebooks, visualization tools and so on
- Remember to include your full answer and used visualizations (code and pdfs) in the repo

Have fun!
