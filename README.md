# Hotel-Booking-Analysis
![b99b565b-5336-4cd2-b731-c64c24515600_rw_1200](https://github.com/akeelrashid/Hotel-Booking-Analysis/assets/121357205/d52850a6-6a9b-498a-a79d-2e8cd248a7b6)
This repository contains an exploratory data analysis (EDA) project focused on analyzing hotel booking data spanning from 2015 to 2017. The hotel industry relies heavily on data to understand customer preferences and optimize operations. By extracting actionable insights from this dataset, we aim to identify key factors influencing booking patterns and overall success.
# Problem Statement
Have you ever wondered when is the best time of year to book a hotel room is? or the optimal length of stay in order to get the best daily rate? what if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings.

# Project Summary
The Hotel Bookings Analysis project involves analyzing a real-world dataset spanning from 2015 to 2017, focusing on hotel bookings. This dataset covers bookings for both city and resort hotels. The project aims to clean, analyze, manipulate, and visualize the data to gain insights into the factors influencing hotel bookings. Here's an overview of the project steps:

### Data Import and Cleaning
The project starts by importing essential libraries. The hotel booking CSV file is imported and transformed into a pandas DataFrame. Data analysis and visualization will be conducted using libraries like NumPy, pandas, Matplotlib, and Seaborn.

### Data Exploration
The dataset comprises 119,390 rows and 32 columns with various data types. It is observed that there are 31,944 duplicate rows. Cleaning involves dropping duplicates and addressing null values. Columns like company, agent, children, and reserved_room_type contain null values, with company and agent having the most. Null values in country and children columns are replaced with mode and mean values, respectively. Each variable is analyzed in detail.

### Data Wrangling
Outliers are identified and removed from columns like lead_time, ADR (average daily rate), and days_in_waiting_list. Additional data manipulation involves creating the total_stay column by combining stays_in_weekend_nights and stays_in_week_nights. Similarly, the total_guest column is created using adults, children, and babies.

### Data Visualization
Visualizations are performed to understand relationships between variables. Univariate, bivariate, and multivariate analyses are conducted using various chart types such as bar plots, count plots, and pie charts.

### Correlation Analysis
The project concludes with a heatmap to visualize correlations between different variables in the dataset.

By following these steps, the Hotel Bookings Analysis project aims to provide valuable insights into hotel booking patterns, guest demographics, and factors influencing bookings in the hospitality industry.

