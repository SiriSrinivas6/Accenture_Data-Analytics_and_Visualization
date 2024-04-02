# Accenture_Data-Analytics_and_Visualization
Accenture North America Data Analytics and Visualization Job Simulation on Forage - March 2024

## Task 1 : Project Understanding
### Key roles and responsibilities of a Data Analyst

A data analyst sits between the business and the data.

What do we mean by that?

The Business refers to the client and your internal team members who won’t be involved in detailed data analysis.
They rely on your analysis to make strategic business decisions.
Importantly, not everyone will have a strong understanding of data. Your job is to communicate your data findings simply and clearly for everyone to understand.
 
The Data refers to the relevant data sources that you will clean, process, and use to generate interesting insights for the business.

### Read the brief from Social Buzz
Your first task is to read the brief from Social Buzz and complete a short knowledge check before the call. 

One of Accenture’s Managing Directors, Mae Mulligan, is the client lead for Social Buzz.

She has reviewed the brief provided by Social Buzz and has assembled a diverse team of Accenture experts to deliver the project.

Mae has scheduled a project kick off call with the internal Accenture project team for tomorrow morning.

Ahead of the call, Mae has shared the project brief so you can get up to speed on what Social Buzz need help with.

Read the brief to:

Understand the client and business problem at hand.
Identify the requirements that need to be delivered for this project.
Identify which tasks you should focus on as a Data Analyst.

Complete the knowledge check to move onto the next step. You can attempt each question in the knowledge check as many times as you like!


Brief from Social Buzz
[Click here](https://github.com/SiriSrinivas6/Accenture_Data-Analytics_and_Visualization/tree/427fd0ddf01db00f39cff9be00dd0d24e3b878d9/Task%201)
 

## Task 2: Data Cleaning & Modeling
### Let's dive into the data

The client has sent through:

7 data sets - each data set contains different columns and values
A data model - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.
There is a lot of information here and it’s easy to get lost in the data. So, to make sure you are using the right data to answer the business questions you’ll follow these steps:

Requirements gathering
Data cleaning
Data modelling
[Data Mode](https://github.com/SiriSrinivas6/Accenture_Data-Analytics_and_Visualization/blob/222e328cccb9f116d208130a7c86bd22202abf55/Data%20model.pdf)

### Data sets - Quick Explanation

The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
So, to figure out popularity, we’ll have to add up which content categories have the largest score.

But! Before we begin to work with the data sets, we’ll need to ensure that the data is clean and ready for analysis…
[Data Sets](https://github.com/SiriSrinivas6/Accenture_Data-Analytics_and_Visualization/tree/79b334986354cd499c0a8733c518cbe696df3573/Data%20Sets)

### Data Modelling

1. Create a final data set by merging your three tables together

using the Reaction table as your base table, then first join the relevant columns from your Content data set, and then the Reaction Types data set.
#### Use a “VLookUp” formula
 
2. Figure out the Top 5 performing categories

Add up the total scores for each category.
#### Use the “Sum If” formula

The end result should be one spreadsheet which contains:

A cleaned dataset
The top 5 categories

You can use Excel or any other tool of your choice to create your final data set.
[Cleaned Data Set](https://github.com/SiriSrinivas6/Accenture_Data-Analytics_and_Visualization/blob/43b1d1fb559e864ecb272cf69d2cdea7482c2105/Task%202%20Edited.xlsx)

## Task 3: Data Visualization & Storytelling

### Create your charts
![Bargraph](https://github.com/SiriSrinivas6/Accenture_Data-Analytics_and_Visualization/blob/24f0d387b87c96ae5e5b4b3bfd0496da8c332929/Screenshots/1.png)
![Piechart](https://github.com/SiriSrinivas6/Accenture_Data-Analytics_and_Visualization/blob/db0b1ba7a4061a8f715a99df8108c034781979e4/Screenshots/2.png)

The final step of this task is to populate slides 7 - 10 with data insights.

We know that the client wants to understand the top 5 content categories. Have a think about what are the best ways to present this? In a pie chart? In a bar chart?

There are also some other interesting insights that we might want to share with them. For example:

How many unique categories are there?
How many reactions are there to the most popular category?
What was the month with the most posts?
