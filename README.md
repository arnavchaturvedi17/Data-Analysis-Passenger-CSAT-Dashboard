# Portfolio Project (Data Analysis) Passenger CSAT Dashboard.
### Arnav Chaturvedi
### Project Role: Data Analyst – Transport - Aviation Industry.

## About Me:
I am a financial analysis enthusiast with a strong skill combination of advanced finance domain/subject knowledge along with other related skills including data analytics, data science experience and business domain knowledge.
I have a strong analytics skill set, especially in Excel, SQL and Tableau.
With prior experience managing and analyzing large datasets, I have developed impactful solutions such as dynamic interactive dashboards (such as fatality data analysis, sales data analysis, financial data analysis; to name a few), helping business users make informed decisions.
I specialized in implementation of end-to-end financial and data analysis projects... from business requirement gathering to data gathering, data cleaning/pre-processing, data analysis, data visualization, translating complex data insights into actionable recommendations for organization.

###  The Dashboard.	Please visit my Tableau Public account.
* Dashboard Link: [https://public.tableau.com/app/profile/arnav.chaturvedi/viz/BritishAirwaysReviews_17349888827570/CompleteDashboard](https://public.tableau.com/app/profile/arnav.chaturvedi/viz/BritishAirwaysReviews_17349888827570/CompleteDashboard)
  
## Portfolio Project Overview:
British Airways (BA), one of the world’s leading airlines, has a rich history of providing air travel services to millions of passengers each year. The airline has grown to become a major player in the aviation industry, known for its extensive network, quality service, and commitment to passenger comfort and safety. As the airline industry becomes increasingly competitive, maintaining high levels of customer satisfaction is essential for retaining customers and fostering loyalty.
In recent years, the proliferation of digital communication channels has led to an explosion in customer feedback. Passengers now share their experiences through various platforms, including in-flight surveys, online reviews, social media, and direct communications with customer service. This feedback contains valuable insights into passengers’ experiences, preferences, and expectations.
Analyzing this feedback effectively allows British Airways to identify strengths and weaknesses in their services, respond to customer needs more efficiently, and make data-driven decisions to enhance overall customer satisfaction. By leveraging data analysis and science techniques, we can transform raw customer feedback into actionable insights that can drive strategic improvements and ensure a superior travel experience for its passengers.
The global airline company has lots of CSAT (Customer Satisfaction) and Survey (Customer Ratings Reviews) data available which was gathered from passengers using survey applications/tools. The Airline PR (public relations) department wants to analyze this data and present meaningful and actionable recommendations to other airline management teams. 
As a data analyst, I created this end-to-end portfolio project for data visualization with an interactive dashboard.   
* End users of this dynamic and interactive dashboard will be able to pick the metrics they would like to see with a simple click, so they can change between average overall CSAT ratings or food ratings etc.
* End users would also have other useful filters to find exactly the data points they are looking for.
* Each of the filters are dynamic themselves so users can pick the date or specific country they are interested in.
Passengers were chosen for this survey across various countries, flight routes, aircraft types, and passenger classes, to provide their satisfaction ratings in various service categories such as overall rating, seat comfort, cabin staff service, food, ground service, value for money, and entertainment.

## Business Problem Scenarios, Objectives and KPIs:
The airline management team would like to analyze and get data insights into this collected CSAT reviews data and identify some actionable recommendations for continuous improvements in flight operations.
* Detect patterns and unveil insights to gauge overall sentiment and identify common issues related to passenger satisfaction and dissatisfaction.
* Develop effective flight operations using customer satisfaction data based on flight plans, such as cabin staff service, ground service, type of traveler, and seat type etc.


## Target Stakeholders:
This dynamic analysis dashboard will be used for the following job roles to increase their productivity and achieve business goals. 
* VP and Managers – Flight Operations
  * Manages the day-to-day activities of the airline, including flight scheduling, flight dispatchers, ground crews, pilots, and flight attendants.
  * Flight planning, dispatch, flight watch, operations control, and maintenance planning.
* VP and Managers – Maintenance
  * Aircraft maintenance.
* Business Analysts

## Skills and Applications used: 
•	SME (Subject Matter Expertise)
  * Business requirement gathering skill and techniques.
  * UI/UX – Guidelines that define how a user interface should look, feel, and behave. They help ensure that users have consistent and predictable experience when interacting with a dashboard.
  * Data cleaning, pre-processing.
* Tableau – Desktop and Public.
  * Data Import as ‘Tableau tables’ – data source (CSV data file, Database Tables)
  * E-R (Entity-Relationship) diagram – Relationship between ‘BA_Reviews’ and ‘Countries’ tables. This is used for filters on the dashboard.
  * Data Visualization - Interactive Dashboard Filters which allows one to toggle between various metrics.
* Microsoft Excel 
  * Knowledge of formulae and functions to be used in any typical data analytical solutions.

## Solution Approach and Process to build this project:
* After receiving the datasets, I interacted with business users from the customer experience team to understand their business requirements and expectations.
* Worked on datasets for data cleaning and pre-processing based on business requirements.
* Built the Tableau dashboard and worked hand-in-hand with business users for UAT (User Acceptance Testing).
* Data Imported as ‘Tableau tables’ – data source (CSV data file, Database Tables).
* E-R (Entity-Relationship) diagram – Relationship between ‘BA_Reviews’ and ‘Countries’ tables. This is used for filters on the dashboard.
* Interactive Dashboard Filters – Allow toggling between various metrics
* Summary Metrics on top for quick data insights.

## Dataset Overview: Data Preparation Process (Data gathering, Data Cleaning, Data Transformation): 
* Data Gathering – The Dataset (Microsoft Excel/ CSV File).
  * Data Sheet: 2 CSV files (‘ba_reviews.csv’  and ‘Countries.csv’)
  * Data is loaded onto the Tableau Drop-down list of all income/expense categories which can be modified as per future needs.
* Data Cleaning (Common cleaning):
  * Data type conversion. Ensuring proper data types for each value to facilitate analysis.
  * Handling Missing Values. Identifying and addressing missing data points to maintain data integrity.
  * Dealing with Duplicate Entries. Detecting and removing duplicate records to maintain dataset uniqueness.
  * Handling Outliers. Frequency analysis has been utilized to identify outliers in ordinal data. The analysis did not show significant evidence that less frequent levels should be considered as outliers.
* Data Pre-Processing and Transformation.
  * Cell formatting, spelling correction
## Data Analysis & Visualization – Dashboard, Reports, Charts, Key findings, Data Insights:
* Standard UI/UX experience for business users.
* Created a very dynamic and interactive dashboard using advanced features; when end users pick a metric from the filter list, the selected metric becomes a ‘filter’ itself, to show all relevant data on dashboard charts. All maps and charts on the dashboard change dynamically to show the user selected metric values in them. This is what makes the user experience very useful for them.
* Tableau Sheet - Map. 
  * Provides data on the dashboard map with zoom in and zoom out features to drill-down analyze. 
  * Created a ‘Geographic Role --> Country/Region’ header from an existing column (place) to use as geographical location for the Tableau map generation.
  * Created List type ‘Parameter’ (Pick a Metric) for the filter.
  * Created ‘Calculated field’ (Metric Selected) with a CASE formula. This is used to show the average ratings values as ‘color marks’ in the geographical map.
  * Customization of the map for best UI/UX such as background map, background layers, coastlines, and color schemes.   
  * Dynamic ‘Title’ values based on ‘Parameter: Pick a Metric’ values (Filters). This will change the chart titles interactively for end users.
  * Created new ‘Filter Fields’ such as month, seat type, aircraft, etc. to use as filters on the dashboard and applied to all data in the dashboard.
  * Customized the ‘Tool-Tip’ for Tableau Maps for data visualizations.  
* Tableau Sheet - Summary Metrics.
  * Created ‘Measure Names’ to show ratings average values on top of the dashboard.
* Tableau Sheet - Line Chart (Trending).
  * Created a continuous month column and selected metrics for the trending line chart. This shows the trending line chart for the average value chart for a user selected metric (i.e. filter).
* Tableau Sheet – Bar Charts.
  * Cutomized a bar chart for UI/UX standards and data sorting.
  * Dynamic ‘color scaling’ on the bar charts based on the metric values.
* Tableau Dashboard – The final dashboard.
  * Combined all visualization components created above (filters, map, line chart, bar chart etc.) into a single dashboard.
  * Created a ‘Floating’ dashboard object for the best user experience across various devices.
  * Formatted the layout of organization and visual customization (look and feel, UI/UX color schemes, ).
  * Published and shared on my Tableau Public account (my portfolio projects). 
 
* Refer to the screenshots below for the Tableau Dashboard for this solution.

## Portfolio Project Documentation (Final Conclusion):
### Documentation: 
* ReadMe-Data Analysis-Passenger-CSAT-Dashboard.docx
### Output File (Published on my Tableau Public account):
* Data Analysis-Passenger-CSAT-Dashboard.twbx

###  The Dashboard.	Please visit my Tableau Public account.
* Dashboard Link: [https://public.tableau.com/app/profile/arnav.chaturvedi/viz/BritishAirwaysReviews_17349888827570/CompleteDashboard](https://public.tableau.com/app/profile/arnav.chaturvedi/viz/BritishAirwaysReviews_17349888827570/CompleteDashboard)
  
### Sceenshot: Dynamic and Interactive Dashboard.
![image](https://github.com/user-attachments/assets/3bf47ca8-3a8c-441f-87f8-fb426e01927b)

### Sceenshot: Dataset (CSAT Reviews).
![image](https://github.com/user-attachments/assets/1d91cb6e-b882-481c-b2eb-37fcfdd27ee4)
 
### Sceenshot: (Dataset) Countries.
![image](https://github.com/user-attachments/assets/24f91262-7383-44ca-9cc3-a8d0e4f6b263)



 


