# Clustering using K-means
 
The intention of this project is to identify different market segments to later develop a marketing campaign strategy.

## Methodology

First steps, as usual, are cleaning and preparing the data. Here, we handle outliers and missing values is imprecindible. Later, Data Descriptive Statictics to obtain an overall understanding of the distribution of the features.

Next, before doing the Clustering, we need to define how many numbers of groups (or clusters) we want work with. Therefore, to obtain this number we analize the Elbow curve to find the optimal k. Here, we got k=4 meaning that we have 4 groups for our segmentation. 

After this segmentation we export the data to visualize in Tableau the most relevant characteristic of each of the segments.

## Results
Check my results published here: https://public.tableau.com/profile/javiera.vines#!/vizhome/ClusteringAnalysis_15912894366620/Clustergralinfo

Insights:
1. Clusters are grouped by RunRace-Participation and Gender. 
2. Age is not an attribute that differenciates Clusters, because centroids are very alike.
3. MoneySpend, Gender and RunRaces relationship show us that the proportion of Males and Females are very similar in all the categories, therefore we understand that a campaign by Gender can be strategic only to promote both segments differently but, benefits will mostly make a difference between the RunRaces.
4. By doing a heatmap we analysed specifically the amount of MoneySpend in the brand vs Loyalty and the clusters. Here the recommendation is to work with the Loyalty segments 1 and 2 which means that people are very likely to purchase these products. We don’t recommend a campaign with the last 4 loyalty categories due to the small %MoneySpendinBrand.
5. By analysing MoneySpend with the running habits such us: Running Distance and Frequency, we could observe that people who run between 2 and 3 times per week, in sum spend more money than the rest, because there is high volume of people in this category. 
