# Python: Interpreting Household Income of the Black and White Families in Baltimore, MD and Essex county, MA with Opportunity Atlas Data

## Background
On January 30, 2017, Carrie Wells published an [article](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-racial-wealth-divide-20170130-story.html) on The Baltimore Sun called _Report highlights economic disparities between races in Baltimore_. In this article, Wells elaborates on the status-quo of the economic disparity between black and white households in Baltimore city and "how deeply segregated by race and how much race is an indicator of economic position in Baltimore". Wells cites a few reports that numerically illustrate how white households have a significantly higher economic status in aspects such as income, owning homes, and bachelor's degree. 

As Wells mentions how the studys' authors did not make any straightforward recommendations to alleviate the problem or "specific policies", CFED "plans on working with six Baltimore nonprofits over the next year to address economic disparities". It has been three and a half years since the publication of this article, but has there been real progress since then? How do we know if CFED has been successful on closing the economic gap between different racial communities in Baltimore? How is the economic disparity like in my high school's county? We will delve more into the data provided by [Opportunity Atlas](https://www.opportunityatlas.org) to further analyze the economic disparities between black and white communities in Baltimore city and my high school county, Essex county, Massachusetts.

![alt text](https://github.com/schoi74/comparing-household-income-baltimore-essex-county/blob/master/black%20and%20white%20in%20baltimore1.png)
## Business Question
_How can Baltimore city and Essex County, MA both decrease the economic gap of household income between the black and white families, and what metrics should the cities measure to monitor their progress and how does geography and demographics affect the disparity between racial communities?_
## Data Question - Open Data
We'll use open data from one source:
- Opportunity Atlas: this research group constructs ["publicly available atlas of children's outcomes in adulthood by Census tract using anonymized longitudinal data covering nearly the entire U.S. population".](https://opportunityinsights.org/paper/the-opportunity-atlas/) We will be using four datasets from this platform:
  
     i. Baltimore: Original open data on household income for black and white families in Baltimore, MD.
     
     ii. Essex County: Orginal open data on household income for black and white families in Essex County, MA.
     
     iii. It is important to note that there is a difference in demographics in  two regions in terms of diversity of race. There can be margins of error in these household income data as Essex County is a predominantly white county, while Baltimore is more diverse with a bigger black community.
## Data Question - Analysis
We will use Microsoft Excel to answer these questions:

- __What does the household income disparity between the black and white families look like in each city?__ Exploring the visual difference of economic disparity in each city using Pivot Tables and Pivot Charts

- __What are the mean household income for both black and white families in each city?__ Exploring the average household income in each city of both black and white demographics using basic Excel functions

- __How does the household income compare for the black families in both Baltimore, MD and Essex County, MA?__ Exploring the household income for black families in both cities using Pivot Tables and Pivot Charts

- __How does the household income compare for the white families in both Baltimore, MD and Essex County, MA?__ Exploring the household income for white families in both cities using Pivot Tables and Pivot Charts

- __What are the highest average household income from black and white families in Baltimore, MD and Essex County, MA?__ Exploring highest average household income by using data reorganization and vlookups. 

## Data Answer - Excel

### What does the household income disparity between the black and white families look like in Essex County, MA?
![alt text](https://github.com/schoi74/comparing-household-income-baltimore-essex-county/blob/master/black%20and%20white%20in%20essex1.png)

Here, just like the visualization and data of black families in each city, we first notice the massive sample size difference between black and white families in Essex County. As Essex County is considered to be a predominantly white county, the racial diversity is not as profound as that in Baltimore. Even though a similar sample and data size would be more clear to compare and evaluate, we can derive that the household income of white families is significantly higher than that of black families, just like Baltimore. This gives us an overall idea of the status-quo mentioned in the [article](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-racial-wealth-divide-20170130-story.html) and an ideal starting point for CFED or any developmental enterprises can dig deeper to provide equal and just opportunities for all racial groups within cities and neighborhoods.

### What are the mean household incomes in each city?
![alt text](https://github.com/schoi74/comparing-income-employement-rate-baltimore-essex-county/blob/master/average.png)

Here we can see that the household incomes for both black and white families from Essex County are higher than those from Baltimore, MD. Also, within each city, the household income is significantly greater for white families than that of black families. This gives us an overall idea of how geography and race impact the household income and where the cities can start alleviating the disparities in the near future.

### How does the household income compare for the black families in each city?
![alt text](https://github.com/schoi74/comparing-household-income-baltimore-essex-county/blob/master/household%20income%20(black)3.png)

Here we first notice the sample size of black families from Baltimore is almost double the black families in Essex County. Even though similar sample sizes would be ideal to more accurately compare the household income demographics in each city, we can safely assume that geography plays a role. On top of that, the household income for black families from Essex County are generally greater than those from Baltimore. 

### How does the household income compare for the white families in each city?
![alt text](https://github.com/schoi74/comparing-household-income-baltimore-essex-county/blob/master/household%20income%20(white).png)

Here we notice that the sample size of white familes from both cities are closer than that of black families (previous graph). However, the household income of the families from Essex County are generally higher than that of familes from Baltimore, which adds onto the observation and assumption of geography impacting the household income for various reasons that both these cities and delve into deeper to lessen the gap.

### What are the highest average household income from black and white families in each city?
![alt text](https://github.com/schoi74/comparing-income-employement-rate-baltimore-essex-county/blob/master/highest%20average.png)

Here we see the top 5 highest average household income families for both black and white families in both cities. We first notice how the household income of white families in Baltimore are nearly double that of black families, which is the problem we seek to resolve and alleviate. On the other hand, even though there is a significant difference in household income between black and white families in Essex County, the degree is not as significant. 

## Data Answer - Python

### What does the household income disparity between the black and white families look like in Baltimore, MD?
![alt_text]()
![alt_text]()

### What does the household income disparity between the black and white families look like in Essex County, MA?

## Summary - Excel
- The findings show that, in general, the disparity of household income between black and white families in Baltimore is greater than in Essex County.
- The demographics of Essex County is notably less diverse than that of Baltimore city.
- The mean household income of Essex County is greater than that of Baltimore for both black and white families.
- The differences of the highest average household income of those in Baltimore were considerably substantial than in Essex County.
- Bigger data availability and additional sample sizes of families in Essex County would be helpful to more directly compare and grasp a better understanding of the status-quo.

## Summary - Python
The findings 

## Python vs. Excel
Python

## Step-by-Step of Excel Analysis
1. import raw data for Baltimore and Essex County in an Excel spreadsheet.
2. Create data sheets for categories: black families, white families, families in Baltimore, families in Essex County.
3. Create pivot tables for each category into a new sheet.
4. Put name in rows and household income in values.
5. By clicking the down arrow on the top of the column, change the sum of household income to average of household income.
6. By clicking the down arrow on the top of the column, filter the towns to eliminate any data outside of Baltimore city by clicking "contains" then typing in "Baltimore".
7. Reorganize the data in a descending order of household income.
8. Change the numerical values into currency ($).
8. Create pivot charts for the four categories.
9. Delete the horizontal axis with town names as we are only focused on the household income for each of the four categories.
9. Gather all the data so far on one sheet to calculate and create a table for the average of each category.
10. Create an "average" chart.
11. On another sheet, use vlookups to find the top 5 highest average household income families in both Baltimore and Essex County for the town names and household income.
12. Create a bar graph of highest average household income families in Baltimore and Essex County.
13. Add axes titles, chart titles for all the visuals.
14. Change the color of the bars for Essex County to yellow on the "average" graph.

