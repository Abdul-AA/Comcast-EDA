# Exploratory Data Analysis (EDA)-Comcast Telecom Consumer Complaints 
## Introduction

Comcast is the largest American global telecommunication conglomerate. In October 2016, they received a fine of $2.3 million from the authorities after receiving over 1000 consumer complaints within the prior three months. The company's database serves as a repository of public customer complaints filed against Comcast. I will analyze the data from this database to help pin down what exactly was wrong with Comcast's customer service and how the firm could have improved.

## Data Dictionary

#### Ticket #: Ticket number assigned to each complaint
#### Customer Complaint: Description of complaint
#### Date: Date of complaint
#### Time: Time of complaint
#### Received Via: Mode of communication of the complaint
#### City: Customer city
#### State: Customer state
#### Zipcode: Customer zip
#### Status: Status of complaint
#### Filing on behalf of someone: If the complaint was filed on behalf of someone or not

## Objective

The aim of analyzing this data is to help Comcast identify areas they could focus on improving to improve customer satisfaction, thus reducing the likelihood of being reprimanded by the authorities in the future. To achieve this, I will be performing the following EDA steps on the dataset: 

- I will Plot a trend chart that depicts the number of complaints at monthly and daily granularity levels. This trend chart will help us determine the days and months with the highest number of complaints. 
- I will construct a table containing each complaint type's frequency. This table will help us determine the most frequent complaint types.
- I will create a new categorical variable with its values as Open and Closed. Open & Pending complaint status will be categorized as Open and Closed, and Solved will be tagged as Closed. This new variable will be used to plot a stacked bar chart that depicts the state-wise status of complaints. We will be able to visualize how adept each state is at resolving consumer complaints in the bar chart. 
- I will perform a calculation to determine the states with the maximum complaints and the highest percentage of unresolved complaints
- Lastly, I will perform a calculation to determine the percentage of resolved complaints that were received through the Internet and those that were received through customer care calls.


