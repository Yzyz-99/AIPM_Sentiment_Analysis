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

<p align="center">Table 1: Roles and Responsibility </p>

#### Risk Identification Chart (Quality, Cost, Time)

| Control Element | What is likely to go wrong? |	How and when will I know? | What will I do about it? |
| :---: | --- |---|---|
| Quality | The system cannot differentiate the positive or negative sentiment in text correctly. | How: The model has a bad performance which give us bad result.<br><br> When: The problem will be encountered when we train the model. | Tune the model parameters such as learning rate or train a more complex model. |                   
| Cost | 1. High usage of Internet and high bandwidth is required.<br><br>2. The project cost reaches the budget limit | How: Website is loaded at a slow speed<br><br>When: The problem will be encountered when we are doing web scraping. | Discuss with the stakeholders about the usage of internet to upgrade the bandwidth. |    
| Time | 1. Project not able to reach the milestone set as described in the Gantt Chart.<br><br>2. Time consuming to collect the data. | How: The members are stuck with a certain problem and drag all the other team members<br><br>When: The problem will be encountered during the project execution and monitoring phase. | Ask for the help from other members to solve the problem or switch job with another member in the team. |    

<p align="center">Table 2: Risk Identification Chart (Quality, Cost, Time) </p>

#### Project Planning Summary

|Modules/Components (RM)  |	    Budget	        | Schedule	          | Responsibility      |
| --- | --- |---|---|
| Data Acquisition       | RM10000   |  20/10/2021 - 10/11/2021  |  Wong Wei Keng  |   
| Model Building     | RM25000   |  15/11/2021 - 15/12/2021  |  Chooi Keen Yu  |  
| Web Interface System     | RM30000   |  16/12/2021 - 10/1/2022  |  Lau Yong Zi, Sia Sim Eng  |  

<p align="center">Table 3: Project Planning Summary</p>

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

<p align="center">Table 4: Tasks and Estimated Costs</p>

#### Milestone Chart
| Milestone |  Scheduled Completion |  	Actual Completion |
| --- | --- |---|
| Initiation     |22-10-2021   |22-10-2021  | 
| Planing        |12-11-2021   |11-11-2021  | 
| Design         |3-12-2021    |1-12-2021   | 
| Implementation |17-12-2021   |17-12-2021  | 
| Closure        |27-12-2021   |30-12-2021  | 

<p align="center">Table 5: Milestone Chart</p>
	
## D. EXECUTING THE PROJECT
#### Project Design and coding

![ArchitectureOfSystem](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/main/images/Architecture%20of%20system.png) 
<p align="center">Figure 4: Architecture of the system</p> <br> 

![SentimentAnalysisStep-By-StepApproach](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/main/images/Sentiment%20Analysis%20Approach.png)
<p align="center">Figure 5: Sentiment Analysis Step-by-step Approach</p> <br>  

![URLcode](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Code%20snippet%20to%20load%20comments%20from%20URL.jpg)
<p align="center">Figure 6: Code snippet to load comments from URL</p> <br>  

![Trainmodelcode](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Code%20snippet%20to%20load%20trained%20model.jpg)
<p align="center">Figure 7: Code snippet to load trained model</p> <br>  

![predictcode](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Code%20for%20predict.jpg)
<p align="center">Figure 8: Code snippet for predict</p> <br>  

![sentimentprocesscode](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Code%20snippet%20for%20process_sentiment.png)
<p align="center">Figure 9: Code snippet for process_sentiment</p> <br>  

![classresultcode](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Code%20snippet%20for%20class%20Result.jpg)
<p align="center">Figure 10: Code snippet for class Result</p> <br>  

![UI](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/User%20interface%20to%20enter%20website%20for%20reddit%20post.jpg)
<p align="center">Figure 11: User interface to enter website for reddit post</p> <br>  

![piechart](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Pie%20chart%20of%20the%20result.jpg)
<p align="center">Figure 12: Pie chart of the result</p> <br>  

![povcomment](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Most%20Positive%20Comments%20of%20the%20post.jpg)
<p align="center">Figure 13: Most Positive Comments of the post</p> <br>  

![negcomment](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/989c232dfa0e5d34a3fe3f3675a42673bf791aa9/images/Most%20Negative%20Comments%20of%20the%20post.jpg)
<p align="center">Figure 14: Most Negative Comments of the post</p> <br>  


## E. COMPLETING THE PROJECT
### Closing Checklist

 i. Acceptance/Project Completion Form Sign-Off 
 
 ![Project Completion Form](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/9e3354a581f4edc239a526df7dbd1366b0e58179/images/Project%20Completion%20Form%20Sign-Off.JPG)
 <p align="center">Figure 15: Acceptance/Project Completion Form Sign-Off </p>

 ii. Lessons Learned Document 
 
 ![Lessons Learned Document](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/9e3354a581f4edc239a526df7dbd1366b0e58179/images/Lessons%20Learned%20Document.JPG)
 <p align="center">Figure 16: Lessons Learned Document  </p>
 
 iii. Final Project Report 
 
### 1.0 Project Objective
- To develop an AI web-based application system that are able to analyze the business sentiment based on the reddit URL. 
- To classify the comments as positive or negative using VADER based on the sentiment score. 
- To implement and compare the algorithm for automatic classification of text into positive and negative. 

### 2.0 Summary of Project Result 
As a result, this system able to anlayse the input based on Reddit URL and able to provide the negative and positive analysis on the particular URL.  
In general, this application allows company to analyse their customer feedback on their products. This approach is an efficient way to help company to know about the trend of their product as they can view the percentage of positive and negative comments. The negative comments may mean the weakness of the product as positive comments means the strength of the product. They can also view the comments by giving them a better understanding of their product’s strength and weakness. 

### 3.0 Original and Actual Schedule 
The project member sticks to the Gantt chart scheduled so, the actual progress fits the original schedule.

### 4.0 Original and Actual Budget
The actual budget matches the original budget, which means that the team has followed the budget planned at the beginning of the project and does not use any excessive money.

| Task  |  Estimated Costs |  Notes |
| --- | --- |---|
| Project Management    | RM 119,350  |  project manager,project team members, contactors , research  |
| Hardware   | RM 43,000  |  laptop, server |
| Software  | RM 42,000  |  licensed software, software development ,software defects ,cloud server  |
| Testing  | RM 64,900  |  online course, project team mambers  |
| Reserves  | RM 55,500 |   |

<p align="center">Table 6: Original and Actual Budget</p>

### 4.1 Cost Estimation
![Costestimation](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/39a8cf1fcb2734b91d684084cb3d446ff3ea642d/images/costestimate.JPG)


![Costestimation1](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/39a8cf1fcb2734b91d684084cb3d446ff3ea642d/images/actualbudget.JPG)
 <p align="center">Figure 17: Cost Estimation  </p>
 
### 4.2 NPV Value 
![NPV](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/39a8cf1fcb2734b91d684084cb3d446ff3ea642d/images/NPV%20value.JPG)
 <p align="center">Figure 18: NPV Value   </p>

### 5.0 Transition Plan
The Insight Sdn.Bhd staff will provide fully support when require. The main work of support provided by The Insight Sdn.Bhd on the Sentimental Analysis in Business system are shown below: 

i)   Maintain the system

ii)  Handle errors and manage update for the Sentimental Analysis system 

iii) Provide user guidelines for Intel staff to use the system 

iV)  Report information to senior management on monthly basis 
 
 iv. Close Contract 
 
 ![Close_Contract](https://github.com/Yzyz-99/sentiment-analysis-in-business/blob/3c90a4269834b3a265a5a66655fffe6a7b75c7f4/images/close%20contract.JPG)
  <p align="center">Figure 19:  Close Contract   </p>

## F. PROJECT PRESENTATION

--> insert video link
