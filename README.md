# Power-BI-Airplane Crashes 1910-2020

This is a Project i have developed using Microsoft Power BI. 
so help ME GOD Thank You.
# Power-BI-Historical Plane Crashes 1910-2020

![Slide1](https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/173084446.0.1415060900.webp)

##  Introduction
This is a Power BI project on Airplane Crash analysis over a time series of Plane Crash leading to Fatalities, Airplane Crash for 110 consecutive years (1910 and 2020).This dataset contains all of the plane crashes that happened throughout history. 


## Data Source:
The data used in this project is a modified dataset known as Airplane Crash;  
* Airplane Crash Sample Data [kaggle datasets download -d abeperez/historical-plane-crash-data)
* Modified Dataset used in this Project [https://www.kaggle.com/datasets/abeperez/historical-plane-crash-data/data](https://docs.google.com/spreadsheets/u/2/d/1xkWC6Jlk_YZECHbpUtoc8AEiPb9jfcld/edit?usp=drive_web&ouid=114068862415751566917&rtpof=true)

## Problem Statement
This project aims to analyze airplane crashes over time, examining trends and identifying key factors that have influenced the frequency and severity of these incidents. By investigating historical data, the project seeks to answer the following key questions:
1. What are the primary causes of airplane crashes?
2. What risk factors are most strongly associated with airplane crashes?
3. How has the crash rate changed over specific time periods?
4. Which regions have experienced the highest number of fatalities due to airplane crashes?

## Power BI and Analytics Technical Skills:
+ Project Planning and Documentation
+ Data Gathering
+ Power Query
+ Data Modelling
+ Report Design
+ Data Visualization
+ Data Analysis Expression (DAX)
+ Business and Analytics Reporting
+ Performance Optimization
+ Deployment and Power BI Service
+ Feedback and Continuous Improvement
  
## Data Modelling
To optimize the performance of the data model, a DAX table was created using the DAX function. The dimension tables does not connect to the corresponding DAX table.
The diagram below shows the data model.  
<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/model%20plane%20crash.png" width=50% height=50%>

## Report Design and Visualization
The Report Canvas was designed in PowerBI as canvas background. Here is a sample of the slide in PowerBI   
<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/Report%20Design%20and%20Visualization%20airplane%20crash.png" width=50% height=50%>  
14 pages were created. 
On each page, the new card visual is used to hold Total Fatalities, PAX Fatalities, Crew Fatalities and Other Fatalities, Line Chart is used for the series analysis,the Donught Chart is used for survival comparison while a column and bar chart are adopted for the Cause, Crash site, Operator, and Country analysis respectively. 

| Visuals             |  Visuals |
:-------------------------:|:-------------------------:
<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/card%201%20airplane.png" width=90% height=90%>|<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/last%20slideairplane%20crash.png" width=40% height=40%> 
<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/slide1%20airplane.png" width=60% height=60%> |<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/slide%202%20airplane%20crash.png" width=100% height=100%> 


## Analytics and Insights
The data analysis revealed that;

1. **﻿Trend in Airplane Crashes (1910-2020):**

  + Airplane crashes were significantly higher in the early years (1910-1979). However, there was a sharp decline in crashes from 1980 to 2020, with incidents decreasing by 91.55% (a reduction of 2,872 crashes over 40 years).
  + **Insight**: This trend suggests that advancements in technology, the implementation of stricter safety regulations, and improved training programs have been effective in reducing the number of airplane crashes over time.

2. **Primary Causes of Crashes:**

  + Human factors were identified as the leading cause of airplane crashes, with 9,926 incidents. This is 1,483.09% higher than the category with the fewest incidents, "Other causes," which accounted for 627 crashes.
  + **Insight**: Despite technological advances, human error remains a significant concern in aviation safety.
  
3. **Geographic Distribution of Crashes:**

  + The total number of crashes varied across five countries, ranging from 848 to 6,804.
  + The United States experienced the highest number of crashes, with 6,804 incidents, representing 52.66% of the total fatalities.
  + **Insight**: The concentration of crashes in specific regions highlights the need for localized safety interventions.
  
4. **Crash Sites and Fatalities:**

  + Most crashes occurred near airports (within 10 km), with these incidents resulting in 13,590 fatalities, accounting for 47.62% of the total fatalities.
  + **Insight:** The proximity of crashes to airports suggests that critical phases of flight (takeoff and landing) are particularly vulnerable and require enhanced safety measures.
5. **Survival Rates:**

  + The survival rate in airplane crashes was low, with a fatality rate of 72.57%.
  + **Insight**: The high fatality rate underscores the importance of improving safety measures and emergency response protocols to increase the chances of survival.
6. **Operator with the Highest Casualties**:

  + The Royal Air Force (RAF) had the highest number of casualties, with 2,363 fatalities, accounting for 32.87% of crashes associated with a specific operator.
  + **Insight**: This statistic may reflect the particular risks associated with military aviation operations.

![ConsolidatedDashboard](https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/airplanbe%20crashicon.png)

## Conclusions

1. **Significant Reduction in Crashes**: The sharp decline in airplane crashes from 1980 to 2020, dropping by over 90%, demonstrates the effectiveness of technological advancements, stringent safety regulations, and improved training programs. However, the persistence of human error as the leading cause of crashes highlights an ongoing vulnerability in aviation safety.
2. **Regional Disparities**: The United States accounted for the majority of crashes and fatalities, indicating a regional concentration of incidents. This suggests that while global safety measures have improved, specific regions may require targeted interventions to address localized risk factors.
3. **Critical Phases of Flight**: The high number of crashes near airports and the associated fatalities indicate that the takeoff and landing phases remain particularly hazardous. Despite overall improvements in aviation safety, these phases continue to pose significant risks.
4. **Low Survival Rates**: The high fatality rate in airplane crashes underscores the need for continued efforts to enhance safety protocols and emergency response strategies. The low chances of survival in these incidents point to areas where further improvements are necessary.
5. **Military Aviation Risks**: The Royal Air Force's high casualty rate highlights the unique risks associated with military aviation. This may suggest the need for specialized safety measures and training programs for military operators.
   
## Recommedations
1. **Enhanced Human Factor Training**: Given that human error remains the leading cause of crashes, it is essential to invest in advanced training programs focused on reducing human error. This could include simulation-based training, fatigue management programs, and decision-making under stress.
   
2. **Regional Safety Initiatives**: For regions with higher crash rates and fatalities, such as the United States, targeted safety initiatives should be implemented. These could include region-specific regulations, improved air traffic control systems, and localized safety audits.
3.**Focus on Critical Flight Phases**: To address the high incidence of crashes near airports, efforts should be made to enhance safety during takeoff and landing. This could involve the development of more robust airport safety protocols, improved aircraft design for these phases, and enhanced pilot training.
4. **Improved Emergency Response**: To increase the survival rate in crashes, it is recommended to improve emergency response protocols. This could involve better crash detection and response systems, advanced fire suppression technologies, and more effective evacuation procedures.
5. **Specialized Safety Measures for Military Aviation**: Given the higher risk associated with military aviation, specialized safety measures should be developed for military operators. This might include stricter maintenance protocols, enhanced training for combat scenarios, and improved safety equipment tailored to military aircraft.

**By addressing these recommendations, the aviation industry can continue to improve safety outcomes and reduce the risk of future airplane crashes.**
##  <a name='WhatShouldbeDone'></a>What Should be Done
* First of all, integrate Hotjar into the website.
* Get ready for an A/B test.
* Change the visuals of the global landing page and carry out an A/B test with the old version for seven days.
* Choose the one with the higher conversion rate. Call this Landing Page A. Then get ready for another A/B test.
* Make the navigation of Landing Page A more intuitive and carry out an A/B test with the first version of Landing Page A for seven days.
* Choose the one with the higher conversion rate. Call this Landing Page B. Then get ready for another A/B test.
* Make the copy of Landing Page B more persuasive and the CTA clearer. Then carryout an A/B test with the first version of Landing Page B for seven days.

##  <a name='WhatWillHappenifActionisDelayed'></a>What Will Happen if Action is Delayed
Delaying the improvements of the global landing page will make the company lose more money. This is because the conversion rate will most likely reduce from 0.22% in October to 0.19% and 0.18% in November and December respectively. The reason to this speculated reduction is not far fetched. 

![](Charts/Months%20by%20Conversion%20Rate.png)

The global landing page leads to other subsequent landing pages. The high bounce rate of the global landing page is an indication that many users are not making it to these subsequent pages. 

It's best to effect the recommendations to improve the global landing page while there's still time. At least, for the sake of Roland's health. Just like they say, a stitch in time saves nine.

Click this [LINK](https://amandinancy16.medium.com/the-one-my-thought-process-9787c5d45054) to see my thought process in arriving at these insights

## Deployment to Power BI Service
This Report is deployed to Power BI service from my Microsoft developer account and publish to the web for everyone to have access to it.
[HautSupermarketAnalysis](https://app.powerbi.com/groups/me/reports/66ab0071-4b25-41c8-99fd-fd006603aacd/ReportSection6239a8326550e132bae6?ctid=32796be2-60fb-4da2-8d26-06e5938e6e6b&experience=power-bi)  

To Open a developer Microsoft account, kindly check this article [OpenMicrosoftdeveloperaccount](https://techcommunity.microsoft.com/t5/educator-developer-blog/register-for-microsoft-365-and-power-apps-developer-account-with/ba-p/3490280)

Thanks for taking time to go through this report! 🤝



