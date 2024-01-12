# StrategicThinkingCA2

The aim of the project is to predict what would be a normal price for an airline ticket based on two weeks of prices tracked by a travel search engine and compare the results with prices of tickets bought on the same day.

This will be done by first scraping a travel search engine and building a database with information on price, airline, origin, destination, total number of stops and price, then performing exploratory data analysis and studying which machine learning performs better at predicting ticket prices, and finally comparing it with prices of tickets bought on the same day.

The final goal is to study how much companies increase the price of their flight when you buy it in advance and on the same day, considering what could be a regular price increase as the day of the flight approaches and what could be an abusive increase based on "dynamic pricing" strategies.

# Questions
Are the prices predicted from a dataset where dynamic pricing has been collected for two weeks and up to the target flight date very different from the prices charged on the same day as the flights?.

# Project Management Definition

To create a project management methodology that enables tracking, defining tasks, sharing information with colleagues, and facilitating programme and model development in an easy-tofollow and clear manner, the decision has been made to utilise GitLab. GitLab is a cloud-based platform and service for software development and version control, which empowers developers to store, manage, and collaboratively develop code, as well as unify project planning, source code management, CI/CD, monitoring, and security.

As a way of utilising this platform, it has been established tasks called Issues, which are defined to be completed in a specific timeframe.
To manage each Issue, we have created three branches and three milestones:
  - Main branch.
  - webscraping branch.
  - data cleaning branch.
  - WebScraping Updating milestone.
  - Merging data collection milestone.
  - Cleaning Data collection milestone.

The approach is that upon completion of an Issue, it will be merged into the Main branch (emulating teamwork where we first develop our algorithms, ensuring they are correct and running smoothly, before merging them into the Main branch).

In order to merge each issue as soon as it is complete, it has been created milestones that correspond to moments in the development process that we have defined in order to create the merge request to the main branch from each branch and the issue for which they were intended.

Milestones are achieved by assigning them to issues, which are then broken down into tasks. Once these tasks are completed, they are pushed to the branch they were assigned to and then merged into the main branch.

  - Merging changes on GitLab is tracked by creating merge requests from the corresponding branch to the main one, which can be pushed through the web or terminal.

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture2.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture1.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture3.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture4.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture5.JPG)

## Issue and Milestones roadmap:
  - Issue 1. Web Scraping – webscreaping branch Due date Dec 5, 2023.
    - Task 1: HTML code updating – Due date Dec 5, 2023.
  - WebScraping Updating milestone Due date Dec 5,2023.
    - Issue 2. Data collection – webscraping branch Due date Dec 13, 2023.
    - Task 1: 05/12/2023 Data collection flights from 11-15_12-2023 – Due date Dec 5, 2023.
    - Task 2: 07/12/2023 Data collection flights from 11-15_12-2023 - Due date Dec 7, 2023.
    - Task 3: 09/12/2023 Data collection flights from 11-15_12-20232023 - Due date Dec 9, 2023.
    - Task 4: 11/12/2023 Data collection flights from 11-15_12-20232023 - Due date Dec 11, 2023.
    - Task 5: 13/12/2023 Data collection flights from 13-15_12-20232023 - Due date Dec 13, 2023.
    - Task 6: 15/12/2023 Data collection flights 15_12-20232023 - Due date Dec 15, 2023.
  - Merging data collection milestone Due date Dec 13,2023.
  - Issue 3. Data cleaning -datacleaning branch - Due date Dec 13, 2023.
    - Task 1: Data format transformation2023 - Due date Dec 14, 2023.
    - Task 2: Outliers2023 - Due date Dec 14, 2023.
    - Task 3: Correlation2023 - Due date Dec 14, 2023.
  - Cleaning Data collection milestone - Due date Dec 14, 2023.
  - Issue 4. Machine learning algorithm modelling - main branch - Due date Dec 15, 2023
    - Task 1: Machine learning modelling2023 - Due date Dec 15, 2023.
   
# WebScraping Model

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture13.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture11.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture12.JPG)

# Machine Learning Model

Features
- Airline, Source, Destination, Duration, Total stops, Date, Date scraped.
Targed
- Price

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture6.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture7.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture8.JPG)

![image](https://github.com/EduardoJMatosRomero/StrategicThinkingCA2/blob/main/images/Capture9.JPG)
