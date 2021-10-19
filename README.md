# An Analysis of Kickstarter Campaigns
This is a recommendation of start dates and funding goals based on data collected on similar campaigns. 

---

## Overview of Project ##
This is intended to help the client design a crowd-funding campaign with the greatest likelihood of success. The details of this report are primarily focused on the ideal timing of the launch date and setting a monetary goal within the range of other successful Kickstarters. However, other factors like country of origin also seem to have some bearing on the completion or failure of fundraisers, but would require further investigation before they are incorporated into her fundraising plan.

---

## Limitations of Data and Subsequent Iterpretations ##
There were a few setbacks in getting the COUNTIFS function to work properly while organizing the data on outcomes based on goals. For instance, COUNTIF and COUNTIFS are apparently two different commands. Additionally, the code needed to be manually altered for each of the goal ranges, thus leaving increased room for error and time spent checking for typos. 
	In addition to this, my initial line graph looked similar to the final results, but did not completely match. I forgot to add the subcategory "plays" as a qualifier for the COUNTIFS and had to go back and paste it to the end of each line of code. At one point I had also mistakenly referenced the wrong column from the Kickstarter data set and had to go back and fix the error after the values for the "Number Failed" column kept returning as 0's.
![image](https://user-images.githubusercontent.com/91698325/137844117-e7c7b60b-d134-48db-97bb-a535ba943bc4.png)
I did not encounter similar issues in setting up the Theater Outcomes by Launch Date graph, likely because the pivot table circumvents the need for so much coding in the cells.

---

## Recommendations Based on Findings ##

I would recommend that the client start her Kickstarter fundraiser in May, but avoid October should she need to start during a different month. Additionally, her funding goal should probably not exceed $15,000. 
![image](https://user-images.githubusercontent.com/91698325/137844341-9c8084a8-ff4e-4bfe-87be-108540a48cb6.png)
![image](https://user-images.githubusercontent.com/91698325/137844358-08a3c637-15fd-4cf7-a9fb-731a1436b456.png)
The more expensive goals were not only negatively correlated with success, but also received less in pledges on average than the cheaper projects did. It may be worthwhile to look into an additional line graph to help visualize any correlation between the original goal and how much was pledged. There were a small handful of successful campaigns in the $35,000 to $45,000 range that raised the average of successful Kickstarters by about $2000 from the median. Due to the current lack of insight into why these projects were successful, despite the high price tag, I would recommend that the client stick closer to the median goal of $3000. I included a screenshot of the descriptive statistics bellow, but this chart is not included in the delivered report due to the large volume of data required to maintain it.
![image](https://user-images.githubusercontent.com/91698325/137844441-c12c07cd-2c26-4f1d-93f3-39c572b082ac.png)






