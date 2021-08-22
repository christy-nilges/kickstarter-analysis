# An Analysis of Kickstarter Campaigns

## Overview of Project

  An analysis of several crowdfunding campaigns and how each fared in relation to their launch dates and their funding goals. This is to help up and coming Kickstarters gain a       greater understanding of funding campaigns from start to finish.

### Purpose
  
  The objective is to determine whether there are specific factors that make a funding campaign successful and enable new Kickstarters to set their campaigns to mirror other         successful crowdfunding campaigns.

## Analysis and Challenges
    
### Analysis of Outcomes Based on Launch Date
 
 In order to determine what time of the year is best to launch a crowdfunding campaign, I utilized data of all campaigns launched between 2009 and 2017 across multiple               countries. Creating a pivot table allowed me to group all outcomes (Successful, Failed, Canceled) by month and then I filtered by the Theatre - Parent Category. As indicated by   the graph below, it is easy to visually determine the best and worst month to launch a Theatre campaign.
 
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88639467/130363055-de0eb249-02b1-48b0-a210-ea07bbd10f1d.png)

### Analysis of Outcomes Based on Goals

  In order to determine the best goal range to set on a new campaign, I used a (Count If) function to count the number and percentage of successful, failed and canceled campaigns   in my dataset. As indicated by the graph below, it is easy to visually determine which goal ranges were the most successful.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88639467/130359596-72c4c7de-a602-4ec6-8a9e-d89709c541bf.png)

### Challenges and Difficulties Encountered
  There were no challenges encountered; however, there could have been challenges if the differing functions (Vlookup or Count If) or formulas were not performed correctly. If any   one piece of these are off, it can change the whole outcome which would alter the final analysis. 

## Results

  Based on the analysis pertaining to the Outcomes based on Launch Date, the following can be concluded;
  
     1. The most successful time of the year to launch a Theater crowdfunding campaign is May and June
     2. The least successful time of the year to launch a Theater crowdfunding campaign is December

  Based on the analysis pertaining to the Outcomes based on Goals, the following can be concluded;
      The highest percentage of successful campaigns with a 76% success rate had a goal of less than $1000 and closely following with 73% is the goal range of $1000 to $4999.           Campaigns with a goal of less than $5000 have the most successful outcomes.  

  The analysis performed is based on what data is available and a misrepresentation of the outcome could result due to missing, duplicate and/or errors in the existing dataset. 

  Additionally, a comparison to look at the relation of a successful campaign vs the Country where it was launched could also have been created. There could be a conclusion         formulated that the location of where a campaign is launched could determine the success. A particular country culturally could have a higher love for the Arts.
