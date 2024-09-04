# Power-BI-Historical Plane Crashes 1910-2020 Report

![Slide1](https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/173084446.0.1415060900.webp)

##  Introduction
Aviation has come a long way, transforming from a risky venture in the early 20th century to one of the safest modes of transportation today. However, despite significant advancements in technology and safety, certain challenges remain, particularly those related to human error and regional safety disparities. This project analyzes airplane crashes from 1910 to 2020, aiming to uncover key trends and provide insights that can drive further improvements in aviation safety. With lives at stake, the need for action is urgent, and this analysis serves as both a reflection on past progress and a call to address ongoing vulnerabilities. 


## Data Source:
The data used in this project is a modified dataset known as Airplane Crash;  
* Airplane Crash Sample Data [kaggle datasets download -d abeperez/historical-plane-crash-data)
* Modified Dataset used in this Project (https://www.kaggle.com/datasets/abeperez/historical-plane-crash-data)

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
+ Risk and Analytics Reporting
+ Performance Optimization
+ Deployment and Power BI Service
+ Feedback and Continuous Improvement
  
## Data Modelling

To optimize the performance of the data model, a DAX table was created using DAX functions. However, the dimension tables are not connected to the corresponding DAX table. The diagram below illustrates the data model.
The diagram below shows the data model.  
<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/model%20plane%20crash.png" width=50% height=50%>

## Report Design and Visualization
The Report Canvas was designed in PowerBI as canvas background. Here is a sample of the slide in PowerBI   
<img src="https://github.com/Trigonx1/Power-BI-Retail-Fashion-Project/blob/main/Report%20Design%20and%20Visualization%20airplane%20crash.png" width=50% height=50%>  
Four pages were created for the analysis. Each page features the following visualizations:

+ Card Visuals: Displaying key metrics such as Total Fatalities, PAX Fatalities, Crew Fatalities, and Other Fatalities.
+ Line Chart: Used for series analysis to track trends over time.
+ Donut Chart: Employed for survival comparison to visualize survival rates.
+ Column and Bar Charts: Utilized for analyzing data by Cause, Crash Site, Operator, and Country.

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
1. Invest in Advanced Human Factor Training:

  + **Action**: Develop and implement comprehensive training programs focused on reducing human error in aviation. This includes simulation-based training, fatigue management, and stress-response training for pilots and crew members.
  + **Outcome**: Improved decision-making and situational awareness among aviation personnel, leading to a significant reduction in human error-related crashes..
2. Implement Regional Safety Initiatives:

  + **Action**: Launch targeted safety programs in regions with higher crash rates and fatalities, such as enhanced air traffic control systems, stricter regulations, and localized safety audits.
  + **Outcome**: A decrease in the regional concentration of crashes, leading to more uniform safety standards worldwide
3. Enhance Safety During Critical Flight Phases:

  + **Action**: Focus on improving safety protocols during takeoff and landing phases. This could involve better runway management, improved aircraft design, and advanced pilot training for these critical moments.
  + **Outcome**: Fewer crashes occurring near airports, reducing overall fatalities and increasing passenger confidence in these phases of flight.
4. Improve Emergency Response and Survival Rates:

  + **Action**: Upgrade emergency response systems, including faster crash detection, advanced fire suppression technologies, and more efficient evacuation procedures.
  + **Outcome**: Higher survival rates in the event of a crash, mitigating the loss of life and improving overall aviation safety.
5. Develop Specialized Safety Measures for Military Aviation:

  + **Action**: Introduce stricter safety protocols and specialized training for military operators to address the unique risks associated with military aviation.
  + **Outcome**: A reduction in military aviation-related casualties and crashes, enhancing the safety of military operations.

##  <a name='WhatWillHappenifActionisDelayed'></a>What Will Happen if Action is Delayed
1. Increased Human Error-Related Crashes:

+ If Delayed: Without immediate investment in advanced training, human error will continue to be a leading cause of crashes. This could result in preventable accidents, leading to loss of life and undermining public trust in aviation safety.
2.Persistent Regional Disparities in Crash Rates:

+ If Delayed: Failure to implement regional safety initiatives could perpetuate higher crash rates in certain areas, particularly in regions like the United States. This could lead to continued disparities in aviation safety, with some regions experiencing disproportionately higher risks.
3. Continued Risk During Critical Flight Phases:

+ If Delayed: Without a focus on improving safety during takeoff and landing, the most hazardous phases of flight will remain vulnerable. This could result in continued high numbers of crashes near airports, with associated fatalities.
4. Low Survival Rates in Crashes:

+ If Delayed: Delaying improvements in emergency response and survival protocols could result in continued high fatality rates. This would mean that passengers and crew have a lower chance of surviving a crash, leading to greater loss of life.
5. Increased Military Aviation Casualties:

+ If Delayed: Without specialized safety measures for military aviation, the high casualty rate associated with military operations will persist. This could lead to unnecessary loss of life and weaken military operational readiness.

## In summary, timely implementation of these actions is crucial to continuing the positive trend in aviation safety. Delays could result in preventable accidents, increased fatalities, and persistent safety disparities across regions and types of aviation operations.  


The safety of countless lives hangs in the balance. The data is clear: while we've made tremendous strides in reducing airplane crashes, the persistence of human error and regional disparities reminds us that our work is far from complete. Every day that we delay action is another day we risk lives that could be saved.

Imagine the tragedy of knowing that lives were lost because we hesitated. Families torn apart, dreams shattered—all because the necessary steps were not taken in time. We owe it to every passenger, every crew member, and every loved one waiting at home to act decisively and swiftly.

Let this not be a moment of regret but a turning point. The time to act is now, before another preventable tragedy occurs. Let us commit to making the skies safer for everyone, everywhere.

## Deployment to Power BI Service
This Report is deployed to Power BI service from my Microsoft developer account and publish to the web for everyone to have access to it.
[Plane Crashes 1910-2020](https://app.powerbi.com/groups/me/reports/8c0d8422-e3ea-41d5-ac08-8df5519ebd8e/42703b5c706ce714ea00?experience=power-bi)  



Thanks for taking time to go through this report! 🤝



