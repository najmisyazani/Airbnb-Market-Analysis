## Project Summary:
To analyze guest search patterns and host acceptance behaviors in the Dublin Airbnb market, aiming to identify gaps between guest demand and host supply, and provide actionable insights to increase bookings and improve market efficiency.

## Dashboard Overview:
![](https://github.com/najmisyazani/Airbnb-Market-Analysis/blob/main/Airbnb%20Market%20Analysis%20Dashboard.png)

## Technical Details:
- Streamlined data processing by developing an ETL pipeline that successfully imported 35,737 search records and 7,823 host-guest interactions from TSV files, as measured by 100% data integrity in the resulting dataframes, by creating a flexible import function that adapts to various separator types.
- Identified seasonal demand patterns by revealing that October had the highest number of check-ins with 6,780 total inquiries (3,966 rejected, 2,814 accepted), as visualized through a month-wise distribution chart in Tableau, providing insights for targeted marketing and capacity planning.
- Uncovered global market reach by analyzing search patterns from 20+ countries, with the US (1,876 searches), Italy (1,625 searches), and Great Britain (1,457 searches) being the top origin countries, as displayed on an interactive world map in the dashboard.
- Optimized pricing strategy by establishing that the 300-400 price filter range had the fastest host response time of 8.52 hours, compared to the overall average of 10.11 hours, as measured by price range segmentation analysis visualized in Tableau.
- Enhanced understanding of booking preferences by determining that the average length of stay was 4.5 nights, with Tuesday being the most popular check-in day (5.4 nights on average), as shown in the "Number of Nights by Check-in Day" chart.
- Revealed potential areas for improving conversion rates by identifying significant variations in booking success across countries, with the US having a 30.66% conversion rate compared to India's 4.89%, as displayed in the "Top Countries by Search & Bottom Countries by Acceptance" table.
- Optimized data analysis workflow by engineering a function to automate SQL Server database creation and dataframe loading, enabling efficient multi-table queries and analyses, which facilitated the creation of a comprehensive Tableau dashboard integrating multiple data dimensions.
