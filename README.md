# Project 1: SAT & ACT Analysis

## Background

The project provides data collected from ACT and SAT college entrance exams administered in the US on a state by state basis from 2017 to 2018. Using lessons learned through the 1.5 weeks of the course so far we are required to clean the data, do data analysis, visualisation, and hypothesis testing.

## Problem Statement

Using the ACT and SAT 2017/2018 testing data, what analysis can we draw from it and subsequently use this information to improve SAT participation rates?

## Executive Summary

We executed and documented the process of obtaining text-based data, cleaning and organizing in our Python Pandas DataFrames, and plotted data to extract meaningful insights that would assist us in answering our problem statement. 

Data is displayed both in tabular form as well as in Histograms, Scatter Plots, and Box Plots from Python's Seaborn/Matplotlib visualization libraries. Through the use of these displays, assembled with custom-built functions, as well as additional supporting data from unique insight we've extracted, we were able to pinpoint to 3 criterias where we managed to shortlist a single state with growth opportunities for the College Board; New Mexico.  

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**State**|*object*|Final|The state in which test data was collected|
|**ACT_Participation_2017**|*float*|ACT|Participation rate of students by state that took ACT during 2017|
|**ACT_English_2017**|*float*|ACT|Mean score for ACT English tests taken in state during 2017|
|**ACT_Math_2017**|*float*|ACT|Mean score for ACT Math tests taken in state during 2017|
|**ACT_Reading_2017**|*float*|ACT|Mean score for ACT Reading tests taken in state during 2017|
|**ACT_Science_2017**|*float*|ACT|Mean score for ACT Science tests taken in state during 2017|
|**ACT_Composite_2017**|*float*|ACT|Mean composite score for ACT taken in state during 2017|
|**SAT_Participation_2017**|*float*|SAT|Participation rate of students by state that took SAT during 2017|
|**SAT_English_2017**|*int*|SAT|Mean score for SAT Evidence-Based Reading & Writing (ERW) tests taken in state during 2017|
|**SAT_Math_2017**|*int*|SAT|Mean score for SAT Math tests taken in state during 2017|
|**SAT_Total_2017**|*int*|SAT|Mean composite score for SAT ERW and Math tests taken in state during 2017|
|**ACT_Participation_2018**|*float*|ACT|Participation rate of students by state that took ACT during 2018|
|**ACT_English_2018**|*float*|ACT|Mean score for ACT English tests taken in state during 2018|
|**ACT_Math_2018**|*float*|ACT|Mean score for ACT Math tests taken in state during 2018|
|**ACT_Reading_2018**|*float*|ACT|Mean score for ACT Reading tests taken in state during 2018|
|**ACT_Science_2018**|*float*|ACT|Mean score for ACT Science tests taken in state during 2018|
|**ACT_Composite_2018**|*float*|ACT|Mean composite score for ACT taken in state during 2018|
|**SAT_Participation_2018**|*float*|SAT|Participation rate of students by state that took SAT during 2018|
|**SAT_English_2018**|*int*|SAT|Mean score for SAT Evidence-Based Reading & Writing (ERW) tests taken in state during 2018|
|**SAT_Math_2018**|*int*|SAT|Mean score for SAT Math tests taken in state during 2018|
|**SAT_Total_2018**|*int*|SAT|Mean composite score for SAT ERW and Math tests taken in state during 2018|


## Conclusions & Recommendations

In reviewing ACT and SAT participation data from 2017 and 2018, we recommend that the College Board prioritize its marketing and lobbying efforts in **New Mexico**.

The College Board should seize the opportunity to lobbying efforts in New Mexico based on both statistical and environmental factors.  

**New Mexico** is selected based on 3 criterias, first as of 2018 it is a state with no mandatory testing for either SAT or ACT. Secondly, it is a democratic leaning state. Lastly, it has low SAT participation rate of 16% this means that there is a 525% increase in participation in the event that SAT is made mandatory in 2019.

Strategy

1) Lobby the State and Local Governments

The SAT can be offered for free or at a discounted price to students at both the state level and the municipal - even if a state doesn't provide for all. Currently, none of these programs exist at the state level in New Mexico, and a more compelling case can be made in its favor.

2) Leverage State Neighbors' Successes

Makes use of trends from neighboring states like Texas and Colorado. Leaning more towards Colorado due to the similarities in terms of political leaning. 

## Data Sources

2017 SAT Data: https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/    
2017 ACT Data: https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows      
2018 ACT State-by-State: http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf     
SAT Score Structure: https://collegereadiness.collegeboard.org/sat/scores/understanding-scores/interpreting      
ACT Score Structure: https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html  
Colorado Mandatory SAT Test: https://www.testive.com/colorado-sat-change-2017/  
Illinois Mandatory SAT Test: https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html  
Rhode Island Mandatory SAT Test: https://www.ride.ri.gov/InsideRIDE/AdditionalInformation/News/ViewArticle/tabid/408/ArticleId/387/Rhode-Island-to-Adopt-New-State-Assessment-Service-Providers.aspx  
2017 Mandatory Test by States: https://magoosh.com/hs/act/2017/states-that-require-the-act-or-sat/  
2018 Political Leaning by States: https://news.gallup.com/poll/247025/democratic-states-exceed-republican-states-four-2018.aspx  
SAT School Day: https://collegereadiness.collegeboard.org/sat/k12-educators/sat-school-day/about  