# Cricket-data-analytics-project

PROJECT DESCRIPTION:

In this end-to-end analytics project we have 4 steps, their names and descriptions are as follows : 

1. Web Scraping: 

We cannot manually web scrape the data from websites because that would take hours and hours which will be extreme wastage of time and human efforts. At the same time we won’t be using Python libraries because websites may use various techniques to detect and block web scraping, such as IP blocking, CAPTCHAs, and cookies.
Python libraries may not be able to bypass these restrictions and may require additional tools or techniques to circumvent them. So, we’ll be using Bright Data to scrape our data which will be the T20 world cup 2022 data from the espncricinfo website. Bright Data is a web scraping and data collection platform that provides access to millions of real residential and mobile IP addresses from around the world. It is a useful tool for web scraping because it allows users to bypass IP blocking, access geo-restricted content, and collect large amounts of data quickly and easily. It provides access to a vast network of residential and mobile IP addresses, mimics human behavior to avoid detection, and offers a range of customizable settings to suit different web scraping projects.


2. Data Cleaning and Preprocessing: 

All of the data that we’ve scraped will be in Json format and we’ll need to convert it to tabular format for performing all sorts of data transformation,modeling, visualization and deriving insights out of it. So we’ll be using Python Pandas for performing data cleaning and preprocessing before converting the json files into csv files with proper orientation and desired fields. 


3. Data transformation and Modeling: 

Data Transformation: Before creating any visualizations, it's important to prepare and transform the data to ensure it's in a format that's easy to work with. Power BI provides a variety of data transformation tools to help with this process, including merging and splitting columns, changing data types, filtering data, and grouping data. These tools can be accessed through the Power Query Editor in Power BI. Data Modeling: Data modeling involves creating relationships between different data tables and defining measures and calculations that can be used to analyze the data. In Power BI, data modeling is done in the Data view, where you can create and manage relationships between tables,
create calculated columns and measures, and define hierarchies and grouping. By creating relationships between tables, you can create powerful insights and visualizations that show how different parts of your data are connected.


4. Creating custom computing measures and building dashboards for collecting insights:

We’ll be using DAX measures for creating custom measures for the various computational results we need to perform on our dataset so as to build our dashboards on the basis of some metrics. DAX (Data Analysis Expressions) measures are a powerful feature in Power BI that allow users to create custom calculations and metrics based on their data. DAX measures are used to create custom calculations and metrics in Power BI. They can be used to perform a wide range of calculations, including sums, averages, and percentages, as well as more complex calculations such as time intelligence and forecasting. DAX measures are created in the Power BI Desktop, and can be used in tables, charts, and other visualizations. Finally, we’ll be creating dashboards for the visualization of our data by choosing the right visualizations for our data and designing our dashboard in a way that is easy to understand and visually appealing. Overall, using DAX measures in Power BI and creating beautiful visualization dashboards can help you gain insights and make data-driven decisions. By using the right visualizations and design elements, you can create dashboards that are not only informative, but also visually appealing and engaging.
