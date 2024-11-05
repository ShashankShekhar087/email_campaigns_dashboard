# email_campaigns_dashboard
An email campaign dashboard highlighting critical metrics like Open Rate, Click-through Rate (CTR), Conversion Rate, and others. 

Project: Email Campaign Dashboard
Objective:
To develop an email campaign dashboard highlighting critical metrics like Open Rate, Click-through Rate (CTR), Conversion Rate, and others. This dashboard enables the team to make data-driven decisions to enhance campaign success and increase audience engagement.
________________________________________
Data Columns:
1.	Campaign ID
2.	Campaign Category
3.	Campaign Name
4.	Email Subject
5.	Email Sent Date & Time
6.	Recipient Email
7.	Open Rate (%)
8.	Click-through Rate (CTR) (%)
9.	Bounce Rate (%)
10.	Unsubscribe Rate (%)
11.	Total Emails Sent
12.	Total Emails Delivered
13.	Unique Opens
14.	Unique Clicks
15.	Conversion Rate (%)
16.	Revenue Generated ($)
17.	Device Type
18.	Time of Day

Data Transformations:
1. Created a Date & Time Hierarchy (Year, Quarter, Month, Day) from the Email Sent Date & Time.
2. Calculated Average Open Rate, Average CTR, and Average Conversion Rate measures.
3. Formulas used in Excel for key metrics:
4. Open Rate = (Unique Opens / Total Emails Delivered) * 100
5. Click-through Rate (CTR) = (Unique Clicks / Total Emails Delivered) * 100
________________________________________
Visualizations:
1.	KPI Cards
 - Highlights metrics like Total Campaigns, Total Emails Sent, Total Emails Delivered, Average Open Rate, Average CTR, Average Conversion Rate, and Total Revenue.
2.	Line Chart
- Displays timeline trends for Average Open Rate, CTR, and Conversion Rate.
3.	Funnel Chart
- Shows the campaign journey: Total Emails Sent → Delivered → Unique Opens → Unique Clicks → Total Revenue.
4.	Clustered Column Chart
- Compares Average Open Rate and CTR by Campaign Sent Time.
5.	Table
- Ranks the Top 10 Campaigns by Open Rate in descending order.
6.	Pie Chart
- Illustrates Average Open Rate and CTR, segmented by time of day (Morning, Noon, Evening, Night).
7.	Donut Chart
- Analyzes device usage (Desktop, Mobile, Tablet) by campaign count.
8.	Slicers
- Time Hierarchy Slicer: Filters data by Year, Quarter, Month.
- Campaign Category Slicer: Filters data by Campaign Category.
________________________________________
Key Insights:
1. Average Open Rate: 50.33%
2. Average CTR: 25.01%
3. Average Conversion Rate: 5.20%
5. Total Revenue Generated: $3,902,873
6. Trends:
- Lowest Open Rates: Observed in July and October.
- Highest Engagement: Retail.com domains had the highest average Open Rate and CTR.
- Optimal Sending Time: Campaigns sent at night had the best Open Rate and CTR.
7. Device Insights:
- Desktop Usage: Most campaigns were viewed on desktop devices.
8. Top-Performing Campaign:
- Discounted Bundle Price (ID: PUB-2758) had the highest Open Rate of 99.78%.

This concise summary captures the most significant results from the email campaign data and provides actionable insights for enhancing future campaign strategies.

![Dashboard image](https://github.com/user-attachments/assets/accfb07e-8b89-4bcb-a9e6-b0689bf841ea)
