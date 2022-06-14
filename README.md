# Recruitment assignment for Data Scientist / Data Analyst / Analytics Engineer
This task is intended for candidates applying for the aforementioned analytics position in the product insights team at the data science tech hub. This assignment is built around some of the technologies used in our production environment.

We are super happy to have you considering a position in our team. The case below should hopefully give you a little insight into some of the most common challenges we face as a team.

## Introduction
The data science department helps Visma teams with various data science related tasks, where our team focuses on delivering *product insights* at scale. To accomplish this we utilize [Snowplow](https://github.com/snowplow) open source, Google Cloud services, and [Dataform](https://dataform.co/). A big part to deliver this offering is through Google BigQuery where all of our data is stored.

What is Snowplow? All in all, it is a service that tracks, collects and stores behavioral data in a database (read more [here](https://snowplowanalytics.com/)).

## The Challenge
The challenge will demonstrate your knowledge in creating a SQL model as well as your ability to work with Git. We will be using the following dataset [here](https://console.cloud.google.com/bigquery?authuser=0&project=snowplow-cto-office). The link should lead you to our GCP instance of Snowplow and in the explorer you should see a dataset called **snowplow-cto-office > snowplow_hackathonpi**. 

The data is a hashed dataset from an existing product using Snowplow. This product is an ecommerce product in the Norwegian market. To read more about the data model, have a look at this publicly available event dictionary about definitions, [here](https://docs.google.com/spreadsheets/d/1G_Xqdj3qo8MqD5T_YAoMjYGPD380FrqkNbvYBlIkF-A)

### Goal:
**Create a sql statement** that helps us answer the following questions
- How many page views was generated for a specific day?
- How many users are active day by day?
- How many sessions?
- What is the time spent per page_url (hashed)?
- How many customers are active day by day?
- Whats the activity for different user roles (user types)

**Visualize your results** in Data Studio. Bring out data you think is interesting to see.

## Submission
Following will be expected:
- git clone this repository
- create a new branch with label "case-submission-<your name>"
- On your new branch add your sql file in an empty file called "my_submission.sql"
- On your new branch add a link to your Data studio dashboard --> **<here>**

- before merging create a pull request 

## Questions?
If you have questions about the task or would like us to further specify some of the things written above, you can contact the person who gave you the assignment.
