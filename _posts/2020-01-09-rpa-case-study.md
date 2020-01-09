---
layout: post
title: Manual Workflow Automation – RPA Case Study
category: Case study
tags: [case study, RPA, automation]
---
 
## The problem
 
Say you work for a consultancy company and they strike a deal with a client, which mainly consists of you doing a lot of annoying manual work. Here’s a much-simplified list of what you have to do every day:
- You connect to one of their websites’ backend, generate a report with all the not-yet-processed subscription requests, and download it
- Then you have to filter out the records you already flagged and are currently pending an answer from the client
- For each one of the remaining potential subscribers, you need to manually search, in Salesforce, their record, and extract the relevant information, from different pages; you do this by copy/pasting into an Excel file
- Once you have your final list, you must apply a set of rules, supplied by the client, in order to validate the records that meet the requisites, and assign them the correct access rights; the others you send to the client for manual control
- Afterward, all the validated records need to be uploaded back to the initial application, in order to grant the users access to the application

Considering that the daily workload could sometimes be in the tens or even hundreds of records and that for different steps you have to use different file templates and formats (JSON, CSV, XLSX, etc.), how can you deliver results in a timely manner? How can you ensure work efficiency, data quality, and periodic backup?
 

## The solution
 
For simplicity sake, we break our problem into three distinct steps:
1. Initial report extraction
2. Salesforce data extraction and requests validation
3. Upload of the final situation to the client application
 
In this particular case, we consider that the client does not want to grant us access to an API or to the database of the application that holds the subscription data nor to give us privileges to generate an API connection key for Salesforce. We thus end up with two users, one for Salesforce and the other one for the client’s web app, and are limited to only using the front end. 

Let’s get right to it!
 
### 1 – Initial Report Extraction
Here, given the circumstances, we can use a more unorthodox way to deal with the problem. Because we only have access to the front end, we can identify all the HTML elements with which we interact in the process of manually logging in and extracting the report, and feed them to a script that uses Selenium to control a headless web browser and automatically replicate the same behavior. This is a reusable piece of code that can be used anytime, even for other projects (though it might need some adjusting for that).

The file containing the not-yet-processed account creation requests will be saved to a resources folder that is specified in the script.
 
 
### 2 - Salesforce data extraction and requests validation
 
Once we have the initial input data, given that they were submitted manually, we run a series of “cleaning” and normalizing algorithms to prepare for the next steps.

For the Salesforce connection, we use Selenium to log in to the front end and capture the resulting cookie information, more precisely, the session ID. With the session ID, user and password we create our connection string and log into the Salesforce back end and using the data from the initial report, we extract the other pieces of information that we need to conclude our analysis.

The subscription requests are then validated, using a set of rules supplied by the client and the result is saved to a file.
 
 
### 3 - Upload of the final situation to the client application
 
For the last step of the process, we create a robot that reads the final situation of the requests, as determined by the previous script, logs in to the client’s application and, using Selenium, flags the ones that are validated.

In the end, the robot sends an email, to the interested parties, with statistics regarding the current run, highlighting the records that must be investigated further by the representatives of the client.
 
## Final thoughts

This approach is a very flexible one for four reasons:
- We can write only one robot that does everything, or we can divide it (as we exemplified above) in three, or even more parts
- We can run the final product on both a server on a local machine, with only minor adjustments
- The application is portable and it can run on Windows, Linux, macOS and has a low maintenance necessities
- By creating a simple companion web application, it becomes more user-friendly and gives the user more visual information and control options

Some obvious advantages of such an application are that it helps free up a lot of time for the person(s) working on these activities while also lowering the error rate and increasing data quality (by eliminating manual copy/paste and manual text insertion and by leveraging the data cleaning and validation algorithms).

All that was mentioned above was part of an actual RPA solution we helped implement, for a client in the pharmaceutical industry and it is still used to date to validate new account connection requests submitted to their online platform.
