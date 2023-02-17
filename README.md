# Kickstarting with Excel

## Overview

An analysis of the trends in Kickstarter Campaigns of the Play subcategory and the relation between their start date and success rate as well as the relation between their goal amount and success rate

## Purpose

The purpose of this project is to break down the relation between the launch date of a campaign and how the campaign fared (success, fail, etc.) and how these relationships can be used to create a successful kickstarter cmampaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/112291888/188032430-408fe7a6-27d2-4304-8054-a052916dd5c9.png)

The majority of the Kickstarter Campaigns that succeeded in meeting their goal where started in May with a secondary, smaller bump in October. This may be because May is the tail end of Spring and the beginning of summer; more people are likely to be out and about looking to go to sources of entertainment. Another conclusion that may be drawn from the data is that seasonal workers who rely on good weather have more disposable income and are thus more inclined to back campaigns.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/112291888/188032977-0b0bd157-d5c8-4d3f-84fe-782e0b670756.png)

What can be concluded from this analysis is that there is a relationship between the goal amount of the campaign and whether or not the campaign succeeds or fails. The majority of campaigns that succeeded were those under $1,000 and those between $35,000-$45,000 while the majority of campaigns that failed were those with a goal amount between $25,000-$29,999 and $45,000-$49,999.

### Challenges and Difficulties Encountered

The challenge of this analysis is that the original dataset contains so much data that it can be overwhelming, which is why we preform these analysis to break down the data into manageable and understandable formats. Two challenges that I encountered with this analysis are the COUNTIFS formula in Excel and the creation of the table "Outcomes Based on Goal". The challenge I was having with COUNTIFS took me appx. 30 to resolve; I was creating a syntax error by clicking on the original workbook, causing the title to be entered into the formula where it was not needed. I resolved this by looking closer at the creation of my formulas and ensuring that contained the appropriate range and criteria. The second challenge I ran into was the creation of the table seen directly above. I was getting an odd distribution on the line graph, upon returning to the brief I disciovered that I had used the values from the 'Pledge' column and not the 'Goal' column. I preceeded to correct the formulas to pull data from the correct column. Upon fixing this error I got the correct representation of the data.

## Results

The results that be be concluded from this analysis of the relationship between time and goal amount in regards to the success of a Kickstarter campaign are that the most successful campaigns are those begun in May with a goal amount of appx. $1,000. Two additional conclusions that may be drawn from the analysis of campaign outcomes based on their launch date is that historically theater programs are put on and viewed in nice weather or during the holiday season. Second; past October, campaign success begins to decline, this may represent the money that people are spending on holidays such as Thanksgiving and Christmas and not on backing a Kickstarter Campaign. Another conclusion that may be drawn from the analysis of campaign success based on goal is that the percentage of failed campaigns and the percentage of successful campaigns are an inverse of eachother, meaning that the mean percentage of successful campaigns is close to the mean percentage of failed campaigns. The take away from this is that you have just as good of a chance of creating a succesful kickstarter campaign as creating a failed one, so go out and do it!

## Limitations of the Dataset and Reccomendations

One limitation that I noticed in the dataset is the lack of information on the genre of the play that is being funded. It would be interesting to see if there is a relationship between the genre of the play and the percentage of successful Kickstarter campaigns. My recommendation would be to collect date on the genre of all the 'Arts' type categories in the data set to add an additional layer of analysis that would deepen our understanding of the data. 