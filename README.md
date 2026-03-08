# PowerBI-Student-Survey_Retail-Store-Purchase-Analysis
1. Introduction:
   
Retail stores often conduct surveys to understand customer purchasing behavior. In this project, the Student Survey dataset was analyzed using Microsoft Power BI to extract meaningful insights about how students spend money on various categories such as Video Games, Indoor Sports, Outdoor Sports, Books, Toys, and Gadgets.
The dataset also contains information about:
•	Store Location (New York, Los Angeles, Seattle, Boston)
•	Store Setting (Urban, Suburban, Rural)
•	Age of students
•	Total Amount of Purchases
The goal of this project was to create interactive visualizations and dashboards to analyze purchasing patterns across different store locations, store settings, and age groups.
________________________________________
2. Objective:
   
The main objectives of this project are:
•	Analyze student purchasing behavior
•	Compare spending across different store locations and settings
•	Identify age-wise spending patterns
•	Create an interactive Power BI dashboard
•	Implement Row Level Security (RLS) for restricted data access
•	Publish the report to Power BI Cloud Service
•	Configure scheduled data refresh
________________________________________
3. Dataset Description:
   
The Student Survey dataset has 754 entries with the following key attributes:
Column	Description
Age	Age of the student
Store Location	City where the store is located
Store Setting	Type of area (Urban / Suburban / Rural)
Video Games	Amount spent on video games
Indoor Sport Kits	Amount spent on indoor sports
Outdoor Sport Kits	Amount spent on outdoor sports
Books	Spending on books
Gadgets	Spending on gadgets
Toys	Spending on toys
Number of Items Purchased	No. of the items purchased
Exchange	Card/Cash
Total Amount of Purchase	Overall spending by the student
________________________________________
4. Data Visualization Implementation:
   
4.1 Tabular Visualization
A table visualization was created to display the Total Amount of Purchase (TAP) based on:
•	Store Location
•	Store Setting
Conditional Formatting Rules
TAP Value	Color
0 – 35,000	Red
35,000 – 60,000	Yellow
≥ 60,000	Blue
Purpose
This helps identify high-performing and low-performing store segments quickly.
________________________________________
4.2 Matrix Visualization:

A Matrix Visualization was created to display:
Outdoor Sports Spending
Across:
•	Age
•	Store Setting
Conditional Formatting
Color formatting was applied to highlight higher spending levels.
Insight
This visualization helps determine which age group spends more on outdoor sports in different store settings.
________________________________________
4.3 Funnel Chart:

A Funnel Chart was created to display:
Total Amount of Purchase by Store Setting
Store Settings included:
•	Urban
•	Suburban
•	Rural
Configuration
•	Data labels set to Percentage of First
Purpose
The funnel chart helps visualize which store setting contributes the most to total purchases.
________________________________________
4.4 Pie Chart:

A Pie Chart was created to show:
Total Purchases by Store Location
Filtered for:
Store Setting = Suburban
Locations included:
•	New York
•	Los Angeles
•	Seattle
•	Boston
Purpose
This helps compare city-wise spending within suburban stores.
________________________________________

4.5 Scatter Plot:

A Scatter Plot was created to analyze:
Video Games Spending vs Outdoor Sports Spending
Across different Age groups.
Axis
•	X-axis: Video Games Spending
•	Y-axis: Outdoor Sports Spending
•	Legend: Age
Purpose
This visualization identifies correlations between gaming purchases and outdoor sports spending among students.
________________________________________
4.6 Sand Dance Plot:

A Sand Dance Plot was created to compare:
•	Indoor Sports Spending
•	Video Games Spending
Across different Age groups.
Purpose
This visualization helps analyze changes in spending trends across age groups.
________________________________________
5. Row Level Security (RLS):
   
Row Level Security was implemented to restrict data access based on user roles.
Example:
User	Access
Mani	Rural Stores Only
Steps
1.	Create User Mapping Table
2.	Define roles in Power BI Desktop
3.	Apply filters based on store setting
4.	Publish to Power BI Service
5.	Assign users to roles
Benefit
Ensures secure and controlled access to data.
________________________________________
6. Power BI Service Dashboard:
   
After creating the report:
1.	The report was published to Power BI Cloud Service.
2.	A Master Dashboard was created containing:
o	Funnel Chart
o	Scatter Plot
This allows users to quickly monitor key performance indicators.
________________________________________
7. Scheduled Data Refresh:
   
To keep the dashboard updated:
A scheduled refresh was configured in Power BI Service.
Refresh Frequency
6 times per day.
Example Schedule
•	1:00 AM
•	5:00 AM
•	9:00 AM
•	1:00 PM
•	5:00 PM
•	9:00 PM
________________________________________
8. Q&A Feature:
   
Power BI's Q&A feature was used to generate visuals using natural language queries.
Example Queries
1. Average age of students
Result: 14.38
2. Donut chart for total purchases by store location
Locations:
•	New York
•	Los Angeles
•	Seattle
•	Boston
This feature allows users to generate insights without creating manual visuals.
________________________________________
9. Key Insights from Dashboard:
    
Insight 1
Suburban stores generated the highest purchase value, indicating strong student spending in suburban areas.
Insight 2
Students aged 16–20 show higher spending on video games and outdoor sports.
Insight 3
New York and Los Angeles contribute significantly to overall purchase revenue.
Insight 4
There is a positive relationship between gaming and sports spending, suggesting students interested in gaming also spend on outdoor activities.
________________________________________
10. Conclusion:
    
This Power BI project successfully analyzed student purchasing patterns across multiple store locations and settings. Using interactive visualizations, the dashboard provides valuable insights into spending behavior, demographic trends, and store performance.
The implementation of Row Level Security, scheduled refresh, and cloud publishing ensures that the solution is scalable, secure, and suitable for business use.
________________________________________
✅ Tools Used:

•	Microsoft Power BI Desktop
•	Power BI Cloud Service

✅ Visualizations Used:

•	Table
•	Matrix
•	Funnel Chart
•	Pie Chart
•	Scatter Plot
•	Sand Dance Plot
•	Donut Chart

