![Logo](https://github.com/Yzyz-99/AIPM_Sentiment_Analysis/blob/2e234e170de5ddc3e2a005ce018762ebdadc3e7c/images/Logo_company.jpeg)

# PROJECT OVERVIEW
## A. DEFINING THE PROJECT

#### **Project Summary**
In this sentiment analysis project, we need to identify the scope of the project. This system can be used by businesses to detect sentiment in social data, gauge brand reputation, and understand customers. This is system will only accept the text which is in English. Therefore, countries or companies that do not use English as their primary language cannot use this system.
#### Customer : Intel
#### Project name: Sentiment Analysis in Business
#### Project Manager: Lau Yong Zi (B031910376)
#### Team Members 
1. Chooi Keen Yu (B031910335)
2. Wong Wei Keng (B031910295)
3. Sia Sim Eng   (B031910446)

#### Project objectives
- To develop an AI web-based application system that are able to analyze the business sentiment based on the reddit url

- To classify the comments as positive or negative using VADER based on the sentiment score

- To implement and compare the algorithm for automatic classification of text into positive and negative 

## B. PLANNING THE PROJECT

#### Project Management Life-Cycle
The project management life cycle is represented and documented in the form of Gantt Chart which we divide our project into manageable stages with each phases listed that combine our project idea into a working syste.<br>  
![ganttchart](https://github.com/Yzyz-99/AIPM_Sentiment_Analysis/blob/2e234e170de5ddc3e2a005ce018762ebdadc3e7c/images/ganttchart.JPG)
<p align="center">Figure 1: Gantt Chart </p>

#### WBS is constructed to make the works more organizable as listed below. 
It used to breakdown the technical part of the project into several modules such as Project Conception & Initiation, Project Definition & Planning, Project Launch & Execution, Project Monitoring and Project Closure.
![WBS](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/main/images/WBS.png)
<p align="center">Figure 2: WBS </p>

#### Responsibility Assignment Matrices (RAM)

![RAM](https://github.com/Yzyz-99/AIPM_Sentiment_Analysis/blob/2e234e170de5ddc3e2a005ce018762ebdadc3e7c/images/RAM.JPG)
<p align="center">Figure 3: Responsibility Assignment Matrices </p>

| Team members | Roles |	Responsibility | 
| :---: | :---: |---|
| Lau Yong Zi         |   Project Manager     | a. In charge of project planning, execution, monitoring, control, and closure.<br><br>b. Responsible for the overall project scope, team, and resources, as well as the project's success or failure. |         
|| Stakeholder Coordinator | a. Maintain up-to-date stakeholder records that reflect the most recent contact and engagement activity.<br><br>b. Research, create, and manage a database of speaking and event possibilities, and make appropriate recommendations to project team members. |    
| Chooi Keen Yu       | Financial Analysts | a. Perform financial forecasting, reporting, and operational metrics tracking.<br><br>b. Record financial performance and analyzing financial data.  |  
|| Procurement Manager | a. Estimate budget for purchasing tools and requirement.<br><br> b. Maintain good relationship with vendors / suppliers.<br><br> c. Record important data such as billing, receipt and pricing. |
|| Quality Manager | a. Quality process control.<br><br> b. Raw materials quality checking.<br><br>c. Reporting quality issue to management. |
| Wong Wei Keng       | Risk Manager | a. Identify and analysis project risk.<br><br> b. Feedback risk status to management.<br><br> c. Risk management control and contingency plan. |
|| Project Scheduler | a. Develop and manage schedules for projects.<br><br> b. Assist project managers with schedule planning, coordinate tasks, and monitor the timelines of scheduled tasks.<br><br> c. Identify potential scheduling delays and actions to be taken. |
|| Operation Manager | a. Manage quality assurance programs and improve the performance of overall process.<br><br> b. Maintaining and increasing the efficiency of business.<br><br> c. Develop, implement, and review operational policies and procedures.|
| Sia Sim Eng         | Technical Manager | a. Maintenance software and hardware.<br><br >b. Collect user feedback and upgrade the system. | 
|| Implementation Manager | a. Coordinate with the team to implement the system and solutions in support of organizational objectives. <br><br> b. Ensure that the implementation are completed on time, within budget and meet client expectations.<br><br> c. Monitor and evaluate all process to ensure the team meets the objectives. |
|| Test Manager | a. Quality & test advocacy.<br><br> b. Resource planning & management for testing.<br><br> c. Applying the appropriate test methods in the system and managing the test effort for any given engagement.|

#### Risk Identification Chart (Quality, Cost, Time)

| Control Element | What is likely to go wrong? |	How and when will I know? | What will I do about it? |
| :---: | --- |---|---|
| Quality | The system cannot differentiate the positive or negative sentiment in text correctly. | How: The model has a bad performance which give us bad result.<br><br> When: The problem will be encountered when we train the model. | Tune the model parameters such as learning rate or train a more complex model. |                   
| Cost | 1. High usage of Internet and high bandwidth is required.<br><br>2. The project cost reaches the budget limit | How: Website is loaded is slow speed<br><br>When: The problem will be encountered when we are doing web scraping. | Discuss with the stakeholders about the usage of internet to upgrade the bandwidth. |    
| Time | 1. Project not able to reach the milestone set as described in the Gantt Chart.<br><br>2. Time consuming to collect the data. | How: The members are stuck with a certain problem and drag all the other team members<br><br>When: The problem will be encountered during the project execution and monitoring phase. | Ask for the help from other members to solve the problem or switch job with another member in the team. |    

#### Project Planning Summary

|Modules/Components (RM)  |	    Budget	        | Schedule	          | Responsibility      |
| --- | --- |---|---|
| Data Acquisition       | RM10000   |  20/10/2021 - 10/11/2021  |  Wong Wei Keng  |   
| Model Building     | RM25000   |  15/11/2021 - 15/12/2021  |  Chooi Keen Yu  |  
| Web Interface System     | RM30000   |  16/12/2021 - 10/1/2022  |  Lau Yong Zi, Sia Sim Eng  |  

## C. IMPLEMENTING THE PROJECT PLAN
#### Deliverables:
- WBS Structure
- Gantt Chart
- Cost Estimation
- Procurement Management Plan
- Communication Management Plan
- Project Closing Report
- Fully Completed System
#### Tasks and Estimated Costs
| Task  |  Estimated Costs |  Notes |
| --- | --- |---|
| Project Management    | RM 119,350  |  project manager,project team members, contactors , research  |
| Hardware   | RM 43,000  |  laptop, server |
| Software  | RM 42,000  |  licensed software, software development ,software defects ,cloud server  |
| Testing  | RM 64,900  |  online course, project team mambers  |
| Reserves  | RM 55,500 |   |


#### Milestone Chart
| Milestone |  Scheduled Completion |  	Actual Completion |
| --- | --- |---|
| Initiation     |22-10-2021   |22-10-2021  | 
| Planing        |12-11-2021   |11-11-2021  | 
| Design         |3-12-2021    |1-12-2021   | 
| Implementation |17-12-2021   |17-12-2021  | 
| Closure        |27-12-2021   |30-12-2021  | 

	
## D. EXECUTING THE PROJECT
#### Project Design and coding
--> insert diagram 

## E. COMPLETING THE PROJECT
#### Closing Checklist

 i. Acceptance/Project Completion Form Sign-Off 
 
 ![Project Completion Form](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/9e3354a581f4edc239a526df7dbd1366b0e58179/images/Project%20Completion%20Form%20Sign-Off.JPG)
 
 ii. Lessons Learned Document 
 
 ![Lessons Learned Document](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/9e3354a581f4edc239a526df7dbd1366b0e58179/images/Lessons%20Learned%20Document.JPG)
 
 iii. INSERT Final Project Report 
 
##### Project Objective
- To develop an AI web-based application system that are able to analyze the business sentiment based on the reddit URL. 
- To classify the comments as positive or negative using VADER based on the sentiment score. 
- To implement and compare the algorithm for automatic classification of text into positive and negative. 

##### Summary of Project Result 
As a result, this system able to anlayse the input based on Reddit URL and able to provide the negative and positive analysis on the particular URL.  
In general, this application allows company to analyse their customer feedback on their products. This approach is an efficient way to help company to know about the trend of their product as they can view the percentage of positive and negative comments. The negative comments may mean the weakness of the product as positive comments means the strength of the product. They can also view the comments by giving them a better understanding of their product’s strength and weakness. 

##### Original and Actual Schedule 
--> pending to add

##### Original and Actual Budget
--> pending to add

##### Transition Plan
The Insight Sdn.Bhd staff will provide fully support when require. The main work of support provided by The Insight Sdn.Bhd on the Sentimental Analysis in Business system are shown below: 

i)   Maintain the system

ii)  Handle errors and manage update for the Sentimental Analysis system 

iii) Provide user guidelines for Intel staff to use the system 

iV)  Report information to senior management on monthly basis 
 
 iv. Close Contract 
 
 ![Close_Contract](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/3c90a4269834b3a265a5a66655fffe6a7b75c7f4/images/close%20contract.JPG)

## F. PROJECT PRESENTATION

