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

![image]()
