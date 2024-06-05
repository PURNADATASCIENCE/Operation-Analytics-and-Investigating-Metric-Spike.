Advanced SQL PROJECT

Project Description:

Operational Analytics is a crucial process that involves analyzing a company's end-to-end operations to identify areas for improvement. This analysis helps various teams, such as operations, support, and marketing, derive valuable insights from the data they collect.

One key aspect of Operational Analytics is investigating metric spikes. This involves understanding and explaining sudden changes in key metrics, such as a dip in daily user engagement or a drop in sales. It is essential to understand how to investigate these metric spikes to answer such questions effectively.

In this project, the role of a Lead Data Analyst at a company like Microsoft is assumed. Various datasets and tables are provided, and the task is to derive insights from this data to answer questions posed by different departments within the company. The goal is to use advanced SQL skills to analyze the data, provide valuable insights that can help improve the company's operations, and understand sudden changes in key metrics.# Operation-Analytics-and-Investigating-Metric-Spike.

Case Study 1: Job Data Analysis
You will be working with a table named job_data with the following columns:

job_id: Unique identifier of jobs
actor_id: Unique identifier of actor
event: The type of event (decision/skip/transfer).
language: The Language of the content
time_spent: Time spent to review the job in seconds.
org: The Organization of the actor
ds: The date in the format yyyy/mm/dd (stored as text).
#Tasks:

1.Jobs Reviewed Over Time:
Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.
<br>
Task: Write an SQL query to calculate the number of jobs reviewed per hour for each day in November 2020.
<br>
2.Throughput Analysis:
<br>
Objective: Calculate the 7-day rolling average of throughput (number of events per second).
<br>
Task: Write an SQL query to calculate the 7-day rolling average of throughput. Additionally, explain whether you prefer using the daily metric or the 7-day rolling average for throughput, and why.
<br>
3.Language Share Analysis:
<br>
Objective: Calculate the percentage share of each language in the last 30 days.
<br>
Task: Write an SQL query to calculate the percentage share of each language over the last 30 days.
<br>
4.Duplicate Rows Detection:
<br>
Objective: Identify duplicate rows in the data.
<br>
Task: Write an SQL query to display duplicate rows from the job_data table.


Case Study 2: Investigating Metric Spike
will be working with three tables:
<br>
*users: Contains one row per user, with descriptive information about that user’s account.
<br>
*events: Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).
<br>
*email_events: Contains events specific to the sending of emails.
<br>
#Tasks:
<br>
1.Weekly User Engagement:
<br>
Objective: Measure the activeness of users on a weekly basis.
<br>
Task: Write an SQL query to calculate the weekly user engagement.
<br>
2.User Growth Analysis:
<br>
Objective: Analyze the growth of users over time for a product.
<br>
Task: Write an SQL query to calculate the user growth for the product.
<br>
3.Weekly Retention Analysis:
<br>
Objective: Analyze the retention of users on a weekly basis after signing up for a product.
<br>
Task: Write an SQL query to calculate the weekly retention of users based on their sign-up cohort.
<br>
4.Weekly Engagement Per Device:
<br>
Objective: Measure the activeness of users on a weekly basis per device.
<br>
Task: Write an SQL query to calculate the weekly engagement per device.
<br>
5.Email Engagement Analysis:
<br>
Objective: Analyze how users are engaging with the email service.
<br>
Task: Write an SQL query to calculate the email engagement metrics.
