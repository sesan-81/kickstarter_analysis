# kickstarter_analysis

1.	OVERVIEW OF PROJECT

We are helping Louise to figure out how she can fund her campaign project by using data to perform analysis with two different approaches to discover the real intuitions.

Purpose:

The purpose of this project is to show the analysis of the campaigns by launch date and funding goals.

ANALYSIS AND CHALLENGES

CHALLENGES AND DIFFICULTIES 

One of the challenges I encountered was using CONTIFS formular to get the values of number successful, failed and canceled, after putting lots of efforts, I was able to overcome this challenge.

2. Analysis and Challenges

Throughout the analysis, I found trends that were responsible for the success of many plays in the United States, I added data visualization to make it easy for Louise to understand it and make the most of this information.

Since Louise was going to launch her theatre campaign in the US, I filtered the data to display the results for all the theatre fundraisers conducted in the US. I also applied conditional formatting to easily visualize the data by colour-coding the successful, failed and cancelled campaigns.


 ![image](https://user-images.githubusercontent.com/104377031/186783460-218eea0a-0ffc-48a5-b2d4-1f33e2f677b6.png)


Since we found there was a correlation between successful campaigns and the month of the year they were launched, we created a pivot table to help Louise pick the most successful date to start her fundraiser.


 ![image](https://user-images.githubusercontent.com/104377031/186783504-060f5333-7a45-44a5-aaf8-692a4e09a4c4.png)


As for her fundraising goal, we used descriptive statistics to help Louise pick a fundraising amount by finding the median of goal and pledged amounts of successful theatre campaigns so that Louise can pick a realistic amount.

Analysis of Outcomes Based on Launch Date.

I used the following approach to split parent category and subcategory:
Data tab>text column button>convert text to columns wizard>delimited>next>uncheck “TAB” box and check “other”>place a backlash (/) in the box>click next>select text>finish.

I used the formular ”(((J2/60)/60)/24+DATE(1970,1,1)” to get date created conversion.

I used =YEAR(Q2) to extract the year from data created conversion.

Based on the data we had on theatre fundraisers we created a pivot table to filter by successful, failed and cancelled fundraisers based on the month. Once the chart was generated, we were able to observe that campaigns launched during the summer months had a higher success rate compared to the rest of the year. The line graph can be referenced below:



![image](https://user-images.githubusercontent.com/104377031/186783591-2329272c-df11-4935-98b0-ee0337e656f0.png)

 

Analysis of Outcomes Based on Goals

(1) I used CONTIFS Formular to form thr number successful, failed and canceled

e.g, =COUNTIFS(Kickstater!$D:$D,"<1000",Kickstater!F:F,"successful",Kickstater!P:P,"plays") to get the “number successful” for “goal” that is less than $1,000

(2) I used the “SUM” formular to get total project.

(3) I used =ROUND(B2/E2*100,0) for the percentages.

For the analysis on Outcomes Based on Goals, we observed that the if the goal amount is within less than $1000 and up to $14999 the success rate is higher, and the number of failed fundraisers is low. Please reference the line graph below:


 
 ![image](https://user-images.githubusercontent.com/104377031/186783671-1c6352ef-6987-44cb-b04d-9080035af750.png)

 

Challenges and Difficulties Encountered

The biggest challenge I had was when conducting the analysis of Outcomes Based on Goals, when I entered the formula for =COUNTSIFS as I entered the wrong angle brackets which provided me with the wrong values. I spent a few hours trying to figure what was wrong so this actually wasted a lot if my time, so next time I will make sure to be more careful when entering my formulas.

The second challenge was that at some point during the analysis I must have entered or altered some of the values on my spreadsheet and as a result I got the wrong values on one of my tables, so it’s very important to save your progress as you go in separate files to make sure you don’t have to do the ensure process from the beginning.

3.	Result

The following analysis was conducted for Louise to ensure the success of her crowdfunding play Fever, the analysis was based on real world data and trends of thousands of campaigns to provide her with in depth feedback to ensure she achieved her goals'

•	What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the data collected for Theatre Outcomes by Launch Date we can observe that fundraisers launched during the months of April to September have a greater success rate than at any other time during the year. This most likely can be that the summer months are better times to run campaigns are people are more interested in investing in activities.

•	What can you conclude about the Outcomes based on Goals?

(A) BASED ON LAUNCH DATE

May and June were the most successful months while December and November were least successful months respectively.

(B) BASED ON GOALS

Based on the analysis, the campaign was most successful between less than $1,000 and less than or equal to $4,999. Which means targets should be between less $1,000 and $4,999.

Fundraisers with a goal lower than $15,000 tend to be more successful as the amount gets lower, the most successful being a 76% success rate for campaigns under $1000.

LIMITATIONS

•	Data for few years were used in this analysis, however large data would have brought about good and reliable results since the whole analysis depends solely on them. 

•	There isn’t any data on the demographics of the people who pledged in the fundraiser, perhaps if we knew more about the investors, we could also know how to cater campaigns to target goals based on specific ages groups and interests.

WHAT ARE SOME OTHER TABLES AND/OR GRAPHS THAT WE CAN CREATE?

Tables:

Tables of Deadline and timeline would give great analysis of the campaign.

Graphs:

Bar chat, histogram, and pie.

