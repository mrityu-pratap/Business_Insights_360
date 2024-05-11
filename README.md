# Business Insights 360

## Project Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBI in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project's hope is to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

I worked on this project by following the Codebasics Data Analysis Bootcamp 2.0 Course, Link to the course is _[here](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance)_

## Tech stacks

- SQL
- PowerBI Desktop
- Excel
- DAX Language
- DAX Studio (for optimizing the report)
- Project Charter File

## PowerBI Techniques Learnt

- What are all the questions which should be asked before staring the project?
- Creating calculated columns
- Creating measures using DAX language
- Data Modeling
- Using Bookmarks to switch between two visuals
- Page navigation with buttons
- Using divide function to prevent zero division errors
- Creating date table using m language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- PowerBI services
- Publishing reports to PowerBI services
- Setting up personal gateway to set up the auto refresh of data
- PowerBI App creation
- Collaboration, workspace, access permissions in PowerBI services
- and more...

## GitHub

- Uploading Large size files using GitHub LFS
- Tracking the particular type of file extensions for LFS

## Business Related Terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGS - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## About Company

AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors

Recently the company has faced an unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project.

## Questions to ask before starting with dashboard
- What is the objective of building this PowerBI dashboard?
- In what terms the success of this project will be measured?
- What will be time dead-line of the project?
- Do the stakeholders expecting pre-view before the actual release?
- What are all the hopes stakeholders have out of this project?
- What are all fears the stakeholder have in terms of building this dashboard?
- Who are all will be using this dashboard and for what purpose?
- What are all expectation the stakeholders have, by the completion of this project?
- What can go wrong while building this project?
- What are all the resources/ data needed to build this dashboard?
- Is there any inputs from stakeholders in terms of design and views of the dashboard?

After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

## Dataset Understanding.

Understanding what data is available will be more helpful while doing analysis. Before jumping on to the analysis, lets get good understanding of what data is available.

Dimension table : It will have the static data like details of customer and products.

Fact table : It will have the data about the transactions.

There are two Databases:
- gdb041: It has Dimensions table such as markets, customers, products and Fact table such as sales_monthly, forecast_monthly

- gdb056: It has freight cost, gross price, manufacturing cost, pre invoice deduction, post invoice deduction

## Importing data into PowerBI
As the database is MySQL in this project, we need to import the datasets from MySQL database to PowerBI by providing the Database access credential.

## Data Model

- Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- In this project, we have followed Snowflake data modeling method.

![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Data_model.png)

## Dashboard designing
Based on the mock ups received as requirement, the team will start designing the visuals and create measures as and when required

## Home view
In Home view, all the views button will be available. User will land on specific view page by clicking the button

- HomePage
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View

## HomePage
![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Resources/HomePage.jpg)

## Finance View
![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Resources/Finance%20View.jpg)

## Sales View
![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Resources/Sales%20View.jpg)

## Marketing View
![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Resources/Marketing%20View.jpg)

## Supply Chain View
![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Resources/Supply%20Chain%20View.jpg)

## Executive View
![plot](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Resources/Executive%20View.jpg)

you can find the full report file here : [report](https://github.com/mrityu-pratap/Business_Insights_360/blob/main/Business%20Insights%20360.pbix)

## Project Outcome
By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.









