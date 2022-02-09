Project_1
Project_1 US POPULATION MIGRATION AS COMPARED TO HOUSING AFFORDABILITY

APRIL KEY, ERIC EAST, MARKUS SHIPLEY, MARY OLAITAN

![atl](https://user-images.githubusercontent.com/94247881/152705384-1355e58f-ad43-4b15-bad6-627e6b0a2c15.jpg)


picture found in Travel and Leisure 2019



ADDITIONAL NOTES - final notebooks to be graded all have FINAL_ in the path name. 
All images are saved to the files folder for easy viewing. 

Presentation Slide Deck Link : https://docs.google.com/presentation/d/1i_yzQRoSs722q4u_36yFrNm4-lDyv2Jbb3zRRZb3Pc4/edit#slide=id.p



April Key, Eric East, Markus Shipley, Mary Olaitan
Group Project 1 Report: US Population Migration as Compared to Housing Affordability

Data sources: 
•	US Census API 5 year ACS 2014 and 2019
•	Zip code to MSA location database
•	Census homeowner %, reported by MSA
Definitions:
•	MSA: Metropolitan Statistical Areas, encompasses city borders and surrounding suburbs, as well as closely economically, socially, and politically tied adjacent areas
•	Affordability Index: Median Household Income divided by the weighted average of Median Gross Rent and Median Monthly Homeowner Costs
Question 1: What are the fastest growing MSAs in the US based on population growth?
The five fastest growing MSAs, by percentage, among our data set are:
1.	Austin, TX: 15.0%
2.	Orlando, FL: 12.5%
3.	Raleigh, NC: 11.1%
4.	Houston, TX: 10.7%
5.	San Antonio, TX: 10.4%
We also wanted to look at Atlanta specifically, which was 15th by percentage (7.5%), though it was 4th in terms of population growth by persons.
One unexpected conclusion was seeing the rapid growth in Texas, with 3 of the top 5 growing MSAs in our data set.
 
The following figure shows the full set of MSAs by percentage population growth 2014 – 2019 (rolling 5 year):
 

The fastest growing specifically (as compared to the slowest growing for reference):
 
 
In looking at the fastest and slowest growing MSAs in our data set we saw a clear trend of migration from the northeast and Midwest to cities in the south (and Texas in particular):
 
 
Question 2: What are the least affordable MSAs to benchmark against the fastest growing MSAs?
The affordability index we created fell along a tighter range of values than expected, ranging from roughly 0.225 to 0.3 for almost all MSAs looked at, though there were a couple high outliers. Miami, FL and Los Angeles, CA had the highest affordability index (meaning highest percentage of income spent on housing/rent) at approximately .35 each, with San Diego, CA, New Haven, CT, and New Orleans, LA, rounding out the bottom 5 least affordable MSAs with affordability metrics. The top 5 are all coastal cities, potentially with the limited availability and high cost of real estate likely contributing to the low affordability.
The following chart shows the top 3 least affordable MSAs as compared to the fastest growing MSAs we’ve selected for analysis. We did find that the faster growing MSAs were not among the most expensive, lending some support to the idea that affordability may be a factor in population movement, though we were not able to prove causation for this based on our regression analysis.

 
 
Question 3: Are people moving to or from zip codes within the MSAs based on affordability?
When we looked in detail at the zip code level and correlated change in the affordability metric from 2014 to 2019 against the change in population, we did not find a statistical relationship between the variables.
The following scatterplots show our tests of affordability against population for our zip codes, the r-squared value shows essentially no correlation.

 


 
Question 4: Does population growth drive decreased affordability?
Similar to above, we looked at the fastest and slowest growing MSAs (shrinking MSAs) against the change in affordability and found no correlation. The affordability seems to be decreasing across the board regardless of population growth.




 
Bonus Question: How has affordability changed at the macro level across the US?
This question was not part of our initial proposal, but it was clear after diving into this data that affordability was a serious issue across the US. Among the dataset we studied, including 69 MSAs and nearly 200 million people, 86% live in zip codes in which affordability has decreased in the past 5 years, and just 2 MSAs had become more affordable.
The decrease in affordability in nearly all MSAs meant that we couldn’t correlate population growth to change in affordability, affordability was down for 97% of MSAs regardless of the change in population over this 5-year time frame.

 
 	More Affordable	More Affordable (%)	Less Affordable 	Less Affordable (%)	Total
Population	28,398,842	14%	168,538,042	86%	196,936,884
Zip Codes	1,814	20%	7,409	80%	9,223
MSAs	2	3%	67	97%	69

