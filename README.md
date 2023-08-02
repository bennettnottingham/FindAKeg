# Project Description: FindAKeg

## Overview
FindAKeg is a web application that provides keg and beer recommendations based on gathered ratings and data from various sources. The platform is specifically designed to help restaurants and breweries efficiently find top-rated kegs that meet their customers' preferences. By simplifying the keg selection process and providing valuable data on keg prices, availability, and beer ratings, FindAKeg aims to revolutionize the way draft-beer serving businesses acquire kegs, making it more cost-effective and time-efficient.

## Problem Statement
In the world of beer serving businesses, the process of buying kegs has been identified as inefficient and time-consuming. Currently, businesses must individually approach each brewery or beer seller to purchase kegs, leading to excessive effort and expenses. There is also a lack of centralized data on keg prices, availability, and customer ratings, making it challenging for businesses to make informed decisions about their keg selections.

## Solution
FindAKeg will address these challenges by providing a user-friendly platform that aggregates data from various sources to provide keg and beer recommendations. The platform will offer keg price data, availability, and beer ratings for specific beer types, empowering businesses to make data-driven decisions about the kegs they wish to purchase.

## Tableau Dashboard
To provide users with an insightful visual representation of the gathered data, the FindAKeg team created an interactive Tableau dashboard. This dashboard showcases key performance indicators (KPIs) and graphs related to the beer data collected from various sources.

### Dashboard Features:
1. **Top-Rated Beers:** The dashboard highlights beers with an average rating greater than 4.5, allowing users to quickly identify highly recommended beers.

2. **Keg Average Price vs. Keg Average Rating:** This graph presents a clear relationship between the average price of kegs and their corresponding average ratings. Users can analyze how price impacts beer ratings and make informed decisions about budget-friendly yet highly-rated kegs.

3. **Percentage of Kegs from Total Number of Beers:** The dashboard includes a percentage representation of kegs available compared to the total number of beers in the database. This metric helps users understand the availability of kegs within the context of the entire beer selection.

4. **Kegs with Ratings > 3.5 vs. Kegs with Ratings > 4.5:** The dashboard provides a comparative analysis of the number of kegs with ratings greater than 3.5 against those with ratings greater than 4.5. This information is valuable for businesses looking to offer premium kegs with exceptionally high ratings.

### Benefits:
The Tableau dashboard adds a visual dimension to the data-driven decision-making process for draft-beer serving businesses. Users can now easily explore and interpret the collected data, gaining valuable insights into the most popular and well-rated beers, making it simpler to identify kegs that align with their customers' preferences.

The interactive nature of the dashboard enables users to customize their views, filter data, and gain deeper insights into specific aspects of the beer selection. This empowers businesses to optimize their keg choices, enhance customer satisfaction, and potentially increase sales.

![tableau_portfolio](https://github.com/bennettnottingham/FindAKeg/assets/65934399/540e37cb-372f-4352-8951-e74013124572)


## Technology Stack
- Web Scraping: BeautifulSoup and Selenium will be used for data extraction from various sources.
- Data Analysis: Python will be employed for data processing and aggregating beer ratings.
- Database: Microsoft SQL Server Management Studio will host the SQL Server instance for centralized data storage.
- Front-End: A user-friendly web interface will be built and hosted on a local Chrome browser for easy access.

![workflow](https://github.com/bennettnottingham/FindAKeg/assets/65934399/2726409b-b11a-4467-b224-a8a6d139a1de)


## Project Deployment
The final deliverable of the FindAKeg project will be a fully functional web application hosted on a local Chrome browser, providing draft-beer serving businesses with data-driven keg and beer recommendations. The Microsoft SQL Server Management Studio will serve as the centralized database for all essential data.

![FindAKegWebsite](https://github.com/bennettnottingham/FindAKeg/assets/65934399/d35173f6-57f9-475a-9962-c8094c4dd5ce)


![Screenshot 2023-05-09 154143](https://github.com/bennettnottingham/FindAKeg/assets/65934399/6580739b-d949-4984-a724-17285195bb8d)



## Conclusion
FindAKeg aims to revolutionize the process of buying kegs for draft-beer serving businesses by providing a data-driven and user-friendly platform. By centralizing keg price data, availability, and beer ratings, the platform will simplify the decision-making process, saving time and expenses for businesses while ensuring that they offer kegs their customers will genuinely enjoy. With the addition of the Tableau dashboard, users can now easily visualize the collected data, making more informed and efficient decisions about their keg selections.
