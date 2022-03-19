# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to determine how different crowdfunding campaigns performed in relation to their funding goals and launch dates. 

The client had previously found success in the use of data analytics to predict the success of their crowdfunding campaign. In order to further capitalize on that success, the client has requested additional analyses that dig deeper into the impact of campaign launch dates and funding goals. Additionally, they requested this analysis be focused specific to both "theater" and "plays" crowdfunding campaigns.

## Analysis and Challenges

The analysis was conducted through Excel. Source data were provided by the client and were organized by campaign name, description, success rate, and various other components related to the dataset. 

The analysis was primarily conducted through the use of stock functions available in Microsoft Products that assisted in sorting and filtering out unneeded raw data, identifiying outliers, and reframing the data to better visualize patterns or trends. Visualization of the data to determine the presence of trends or patterns was conducted through the use of pivot tables and pivot charts.

A link to the original analysis can be found and downloaded locally [here](https://github.com/sever1sd/kickstarter_analysis/blob/main/Kickstarter_Challenge.xlsx).

### Analysis of Outcomes Based on Launch Date

The analysis of crowdfunding campaign outcomes based on launch date was conducted on any campaign that was tied to theatrical enterprises. The target category was isolated by converting data to a pivot table and filtering out any unrelated "Parent Category" in the dataset. Data was then sorted by "Month" and outcomes of the campaigns. This analysis includes all data from 2010 - 2017. The resulting chart was then converted to a line-chart in order to evaluate any potential trends in outcomes. This analysis can be found in the previously provided file under the "Theater Outcomes by Launch Date" tab.

**Created chart:**

![alt text](https://github.com/sever1sd/kickstarter_analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

The analysis of crowdfunding campaign outcomes based on campaign goals was conducted on any campaign that was specific to theatrical plays. The target subcategory was isolated by creating a separate table (which can also be found in the previously provided file under the tab "Outcomes Based on Goals") that aggregated outcomes based on "buckets" of goal categories. Success, Failure, and Cancel rates were then calculated as a percentage of the total for each bucket category. A line chart was then created to evaluate any possible trends in the data.

**Created Table:**
![image](https://user-images.githubusercontent.com/98677283/159126217-8834d27d-49e7-46ac-942d-c5cdae71fb03.png)

**Created Chart:**
![alt text](https://github.com/sever1sd/kickstarter_analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

There were no readily apparent challenges in scrubbing and analyzing these data. Because the dataset was provided by the client, there were also no challenges in sourcing these data. If this were not the case, some challenge that could have occurred would been

1. Sourcing raw data from reliable locations
2. Scrubbing raw data for gaps or missing information
3. Organizing raw data into readily consumable frameworks

## Results
 After reviewing the data, there are a number of conclusions to be drawn:
 
 **Outcomes Based on Launch Date:**
 1. Theatrical crowdfunding campaigns tend to do better in early summer months (May-June)
 2. Success rates taper off throughout the summer and into the fall
 3. The worst month for theatrical crowdfunding campaigns is December
 4. Cancelations seem largely unimpacted by time of year
 5. There is a brief spike in failed campaigns in the month of October
 
 **Outcomes Based on Goals:**
 1. Campaigns with lower goals tend to do better than campaigns with higher goals
 2. There is a brief spike in success rates for goals between $35,000 and $45,000, but due to sample size for this goal bucket, this could be noise
 

**Limitations of this data:**
1. This analysis does not consider country of origin, which could play a part in the success of a crowdfunded campaign
2. This data does not include contributor demographics, which could impact the success of a crownfunded campaign\
3. This data does not include the location where these plays and theatrical releases took place, population density of location could impact success rates

**Additional potential analysis:**
1. The duration of a crowdfunded campaign and its relationship to success
2. The correlation between the goal size and local population density of theatrical release

**Additional potential charts:**
1. Bar graphs charting the totals for Outcomes Based on Goals to compare the number of campaigns for each goal bucket
2. Histograms of "Success," "Failure," and "Canceled" categories for Outcomes Based on Goals to determine sample distribution and density of each category
