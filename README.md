# Kickstarting with Excel

## Overview of Project

### Background
    Louise started a crowdfunding campaign to help fund her play Fever, with a funding goal of ~$10K. 
    She is close to achieving the goal and want to understand more about possibility of achieving the required funding 
    using the Kickstarter data set. 	

### Purpose
    Purpose of the project is to analyze Kickstarter dataset and provide insights & recommendations on the feasibility of Louise 
    achieving the fundraising goal. 
    
    Explore different visualizations using data from other fund-raising campaigns, primarily based on Launch dates and $goals. 

## Analysis and Challenges

### Analysis Overview
-	Understanding the project scope and the data set

    	I took time to understand the project case and review the data set. I took a note of relevant fields for the analysis and started 
        pivoting the data to understand the patterns and data.

-	Explore for relevant insights  

    	Put together a list of questions that can be answered using the data. Narrowed the list to pick ones in the scope of the assignment. 

-	Learn and familiarize with excel functionalities

### Challenges and Difficulties Encountered

-	Working with aggregations and creating visualization was challenging initially, but with practice and multiple iterations I am able to achieve them.

-	Validating the formula: While using Countifs, it was challenge to verify if the results are accurate. Manually added columns to the excel 
to verify with the results

-	Determining which visualization to use for the custom analysis was difficult, hoping to learn multiple scenarios where 
I will be able to judge best visualization for the analysis.

## Results

### Analysis of Outcomes Based on Launch Date
1.	Highest number of campaigns were launched in successful when launched in May, followed by June and July. Success rates: 67%, 65% and 63% respectively.
2.	Lower number of campaigns were launched in Dec with higher rate of failure (47% failure: 35 out of 75 campaigns)

![Getting started](./resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
- The success rate of campaigns is inversely proportional to the $ value of the goal, with the exception of $35K to 45K range (small sample set of campaigns)

![Getting started](./resources/Outcomes_vs_Goals.png)

### Dataset Limitations
-	Goal Achieved date: Would have helped to understand how long it took on average for the successful campaigns to achieve the funding goal
-	Criteria for staff_pick or spotlight: As most of the successful campaigns are either staff picked or in spotlight, any criteria to identify how a campaign can be staff picked will help Louise effort to secure funds

### Recommendations for additional visualizations
- Campaigns launched in November has **80%** success rate (Play Subcategory and Goal range of $5K to 15K)

   ![Getting started](./resources/Option1_PlayOutcomes_ByMonth_Goal5K-15K.png)

- Staff picked campaigns has **82%** of success rate (Play Subcategory and Goal range of $5K to 15K)

   ![Getting started](./resources/Option2_PlayOutcomes_ByStaffPick_Goal5K-15K.png)

