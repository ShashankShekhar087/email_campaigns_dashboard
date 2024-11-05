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

Interpretation of Email Campaign Dashboard Results
# Overall Campaign Performance:

1. The dashboard shows data for a total of 1,000 email campaigns with over 16 million emails sent, of which approximately 15.95 million were delivered. This high delivery rate indicates effective email distribution and list hygiene practices.
2. Key performance metrics include an average open rate of 50.33%, an average click-through rate (CTR) of 25.01%, and an average conversion rate of 5.20%. These metrics suggest reasonable engagement but highlight potential areas for improvement in driving conversions.
3. Trends:
- The line chart shows fluctuations in average CTR, open rate, and conversion rate across months. The highest open rates occurred in January (55%) and December (51%), suggesting these months may be optimal for engagement, possibly due to seasonal campaigns.
- Conversion rates remain consistently low, peaking slightly at 6% in December, which may reflect end-of-year promotions.
4. Device Preference:
-Device-wise analysis reveals that 52.4% of campaigns were accessed via mobile, compared to 47.6% on desktop. This slight preference for mobile indicates that mobile-optimized email designs could enhance user experience and engagement.
5. Domain-wise Performance:
- Among various domains, "retail.com" achieved the highest average open rate (52%) and CTR (27%), followed closely by "ecommerce.com" and "shop.com". This suggests that email campaigns targeted at retail-related domains may be more engaging, possibly due to product or service relevance.
6. Top Campaigns:
- The table lists high-performing campaigns, with the "Discounted Bundle Campaign" achieving the highest open rate (99.78%) and a CTR of 45.10%. Other campaigns like the "Author Interview Campaign" and "New Release Campaign" also show high open rates but lower CTRs. These results indicate strong interest but suggest that email content could be more compelling to drive clicks and conversions.
7. Open Rate and CTR by Time of Day:
- The pie chart shows that emails sent in the morning and noon achieved the highest open rates, each at 51%, while CTR peaks at 26% in the evening. This trend suggests that sending emails in the morning might optimize open rates, while follow-up engagements later in the day could enhance CTR.
8. Revenue Generation:
- The campaigns have generated a total revenue of approximately $3.9 million, which can be attributed to the relatively high engagement metrics. However, focusing on improving the conversion rate could further boost revenue.
# Recommendations
1. Optimize Campaign Timing:
- Based on open rates and CTR by time of day, consider scheduling emails in the morning for higher open rates and using retargeting in the evening for maximizing click-through rates.
2. Enhance Mobile Optimization:
- Since a significant number of users engage on mobile devices, ensure that emails are mobile-friendly, with clear call-to-action buttons and responsive design.
3. Target High-Engagement Domains:
- Focus efforts on high-performing domains such as retail and e-commerce by tailoring content to the specific interests of these audiences. Campaigns on these domains could yield higher engagement and conversions.
4. Refine Content for Click-Through and Conversions:
- The high open rates but relatively lower CTRs for top campaigns suggest interest but a lack of compelling content or offers to encourage clicks. Consider A/B testing different calls to action, content, and offers to improve CTR and conversion.
5. Leverage Seasonal Trends:
- Given the peak engagement in January and December, plan major campaigns during these months with targeted promotions or limited-time offers to maximize revenue.
6. Increase Focus on Conversion Optimization:
- To boost the conversion rate, consider strategies such as personalized offers, limited-time discounts, or customer-specific recommendations to drive purchases or desired actions after clicking through.
7. Top-Performing Campaign:
- Discounted Bundle Price (ID: PUB-2758) had the highest Open Rate of 99.78%.

This concise summary captures the most significant results from the email campaign data and provides actionable insights for enhancing future campaign strategies.

![Dashboard image](https://github.com/user-attachments/assets/accfb07e-8b89-4bcb-a9e6-b0689bf841ea)
