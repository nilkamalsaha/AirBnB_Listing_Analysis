# AirBnB_Listing_Analysis

## The Situation

You 've just been hired as a Performance Analyst for AirBnB, a platform that allows individuals to rent out their homes for travellers

## The Assignment 

As AirBnB has grown in popularity, it has increasingly become the focus of regulations designed to limit the number of properties listed in each city.

You've been asked to analyze PAris listings, with a focus on pricing. Leadership wants a visual summray of factors affecting pricing and wheather regulations adopted in 2015 impacted listings in the Paris Market.

## The Objectives

1. Explore and profile the data to correct any quality issues
2. Prepare and reformat the data for visualization
3. Visualize the data and identify key insights and recommendations


### Objective 1: Profile & QA the data

Your first objective is to read in the AirBnB listings data, calculate basic profiling metrics, change column datatypes as necessary, and filter down to only Paris Listings.

1.	Import/Open the Listings.csv file.
2.	Cast any date columns as a datetime format.
3.	Filter the data down to rows where the city is Paris, and keep only the columns ‘host_since’, ‘neighbourhood’, ‘city’, ‘accommodates’, and ‘price’.
4.	QA the Paris listings data: check for missing values, and calculate the minimum, maximum, and average for each numeric field.

### Objective 2: Prepare the data for visualization

Your second objective is to produce DataFrames that will be used in visualizations by aggregating and manipulating the listings data in several ways.

1.	Create a table named paris_listings_neighbourhood that groups Paris listings by 'neighbourhood' and calculates the mean price (sorted low to high).
2.	Create a table named paris_listings_accomodations, filter down to the most expensive neighborhood, group by the ‘accommodations’ column, and add the mean price for each value of ‘accommodates’ (sorted low to high).
3.	Create a table called paris_listings_over_time grouped by the ‘host_since’ year, and calculate the average price and count of rows representing the number of new hosts.

### Objective 3: Visualize the data and summarize findings

Your final objective is to build visuals to show the number of new hosts by year, overall average price by year and neighborhood, and average price for various types of listings in Paris' most expensive neighborhood.

1.	Create a horizontal bar chart of the average price by neighborhood in Paris, and make sure to add a title and change axis labels as needed
2.	Create a horizontal bar chart of the average price by ‘accommodates’ in Paris’ most expensive neighborhood, and make sure to add a title and change axis labels as needed
3.	Create two line charts: one showing the count of new hosts over time, and one showing average price. Set the y-axis limit to 0, add a title, and change axis labels as needed
4.	Based on your findings, what insights do you have about the impact of the 2015 regulations on new hosts and prices?
5.	BONUS: Create a dual axis line chart to show both new hosts and average price over time.

FINAL STEPFinal Project QuestionAnswer the following question to validate your completed project.
________________________________________
Which neighborhood in Paris has the highest average AirBnB listing price?
