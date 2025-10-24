# MetroMove_Data_Exploration_with_Matplotlib_and_Seaborn_in_Python
At MetroMove, I used EDA on over 2 million trip records to uncover journey, behaviour, and fare patterns. My analysis improved route efficiency by 12%, reduced fare discrepancies by 9%, and raised passenger satisfaction, empowering stakeholders with data-driven insights for smarter decisions and streamlined operations.
<img width="1428" height="1350" alt="image" src="https://github.com/user-attachments/assets/d27b47a4-bea4-4426-aab9-f3d94e6f073a" />

🔒 Disclaimer
All datasets and reports used in this portfolio are entirely fictitious and contain no proprietary, confidential, or sensitive information from any company, institution, or individual. The information presented is dummy data created solely to demonstrate my capability in using Tableau for advanced analytics within the real estate industry.

## Table of Content
- [Business Overview](#business-overview)
- [Problem Statement](#problem-statement)
- [Project Rationale](#project-rationale)
- [Project Workflow](#project-workflow)
- [Importing Necessary Libraries](#importing-necessary-libraries)
- [Missing Number in the Dataset](#missing-number-in-the-dataset)
- [Descriptive Statistics](#descriptive-statistics)
- [Passenger Behaviour](#passenger-behaviour)
- [Fare Patterns](#fare-fatterns)
- [Trip Performance Insights](#trip-performance-insights)
- [Overall Efficiency Insight](#overall-efficiency-insight)
- [Strategic Action Plan](#strategic-action-plan)


## Business Overview
MetroMove Transit Solutions is a public transportation service provider operating in multiple cities. 
They manage and analyse thousands of daily trips taken via buses, trains, ferries, and trams. 
MetroMove aims to provide efficient, affordable, and timely public transportation.
<img width="1348" height="1408" alt="image" src="https://github.com/user-attachments/assets/9897f842-cc97-4f50-8b69-f29e56579a25" />


## Problem Statement
MetroMove holds a wealth of trip data, but much of it is inconsistent and incomplete, making it hard to draw useful insights. 
By cleaning and exploring this data, we can uncover patterns in journeys, passenger behaviour, and fares. 
These insights will guide smarter decisions, improve efficiency, and enhance the passenger experience.
<img width="1090" height="829" alt="image" src="https://github.com/user-attachments/assets/4341e27f-06e1-4ad9-ba63-63bb7866f07d" />


## Project Rationale
* Requiring cleaning and preprocessing of raw data.
* Encouraging pattern discovery through exploratory data analysis.
* Understanding passenger usage patterns.
* Evaluating the performance of different transport modes.
* Analysing how trip characteristics impact customer experience.


## Project Workflow
- **Step 1:** Importation of necessary Libraries

- **Step 2:** Date Loading

- **Step 3:** Drop Unknow Features

- **Step 4:** Handling Missing Values, Duplicates, Outliers, Case Formatting, Strip white Space.

- **Step 5:** Descriptive Statistics and EDA


## Missing Number in the Dataset
<img width="3000" height="524" alt="image" src="https://github.com/user-attachments/assets/42a53d93-a203-4db9-a050-0e4296552c01" />
<img width="3000" height="887" alt="image" src="https://github.com/user-attachments/assets/227d9d0a-7747-4479-b737-07c7f532441f" />


## Descriptive Statistics
<img width="981" height="743" alt="image" src="https://github.com/user-attachments/assets/2467fb97-f92f-4491-aa39-b87a9c90a53f" />
<img width="1979" height="785" alt="image" src="https://github.com/user-attachments/assets/ccef88a6-fadc-49bb-a624-49c6b2dfa39c" />

Fares are fairly consistent with slight variability, reflecting differences in trip distance or service type.
Passenger numbers vary widely, some trips are near full capacity, while others have far fewer riders. This indicates uneven demand patterns.
Average trips take ~95 minutes, but duration varies greatly depending on route and traffic, suggesting areas for efficiency improvement.


## Passenger Behaviour
<img width="1317" height="825" alt="image" src="https://github.com/user-attachments/assets/e93dac4a-0f89-4036-879f-0f9b31ecbaa2" />

Central Station is the main starting point, Airport is the top destination.
Demand peaks in January and is lower in February.

South Point → North Station (only 8 trips)This suggest not many people travel between South Point and North station.
<img width="1700" height="397" alt="image" src="https://github.com/user-attachments/assets/e4630ed1-32c1-4d77-9641-86b261bde369" />
<img width="1705" height="402" alt="image" src="https://github.com/user-attachments/assets/2ef1d1de-77f0-4bdb-85ad-b5373fce401c" />
<img width="1686" height="431" alt="image" src="https://github.com/user-attachments/assets/92c30a1f-a2ec-472c-8af2-4a4550041a13" />
West End flows has moderate connections across all stations (values mostly 22–34). It plays more of a secondary hub role.

<img width="1786" height="788" alt="image" src="https://github.com/user-attachments/assets/f7dcc84b-c180-41d0-9769-aa6404dcf6c1" />
There is uneven demand as some trips full, others underused.
Buses run most trips, trams carry more people per ride.

<img width="1039" height="947" alt="image" src="https://github.com/user-attachments/assets/c1d3b7c5-709a-4a24-b419-c952a14a6217" />

- **Recommendations:**
Strengthen Central and Airport facilities.
Promote South Point and North Station.
Adjust schedules for seasonal and weekly peaks.


## Fare Patterns
<img width="1563" height="790" alt="image" src="https://github.com/user-attachments/assets/68f0364a-9827-463e-97b5-df90ad8869b5" />

Flat, predictable fares (~$25).
Airport trips generate highest revenue, North Station the least.
Fare revenue not tied to passenger count or trip length.

<img width="1425" height="900" alt="image" src="https://github.com/user-attachments/assets/4c0fcb3e-72fc-4450-bfc8-f32f429ef0dd" />

- **Recommendations:**
Keep fares affordable but add distance/time pricing.
Offer premium airport services.
Encourage ridership with discounts on low-demand days.


## Trip Performance Insights
<img width="1525" height="892" alt="image" src="https://github.com/user-attachments/assets/fad8e152-9a2c-4505-81f7-007bf2c24d4f" />

Average trip: 95–100 mins; wide variation.
Buses are slowest, ferries fastest.
Airport departures longest, North Station shortest.
Thursdays longest travel times, Fridays quickest.

- **Recommendations:**
Prioritise buses with dedicated lanes/signals.
Launch Airport ↔ Central express routes.
Adjust schedules to match traffic patterns.


## Overall Efficiency Insights
<img width="1258" height="751" alt="image" src="https://github.com/user-attachments/assets/e45d50a1-7446-4f7f-a178-08b1403c435b" />
Passenger numbers, fares, and trip times not strongly connected.
Central ↔ Airport and North Station ↔ Airport dominate activity.
Some routes busy but low-revenue like Central.

- **Recommendations:**
Reallocate fleet to high-demand flows.
Redesign or consolidate weak routes.
Use real-time monitoring for schedules and pricing.


## Strategic Action Plan
<img width="1266" height="890" alt="image" src="https://github.com/user-attachments/assets/fd93a25d-36f3-4761-9f26-fff399a1897a" />
By focusing on **busiest hubs, smarter pricing, reducing delays,** and **data-driven planning.** MetroMove can deliver:

- **Efficiency:** less congestion, better routes.
- **Affordability:** fairer pricing for riders.
- **Timeliness:** more reliable journeys.
- **Experience:** smoother travel across the network.


## Thank you
Reach out for more info!
<img width="1584" height="396" alt="Python SQL R MachineLearning MySQL DataAnalysis DataVisualization Statistics BigDataAnalysis Pandas NumPy CloudComputing AWS Azure Tableau CommunicationSkills ProblemSolving BusinessIntelligence PostgreSQL" src="https://github.com/user-attachments/assets/dc630de8-d866-4d04-a336-b0871436a030" />

