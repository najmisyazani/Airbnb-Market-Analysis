## Project Summary:
To analyze guest search patterns and host acceptance behaviors in the Dublin Airbnb market, aiming to identify gaps between guest demand and host supply, and provide actionable insights to increase bookings and improve market efficiency.

## Dashboard Overview:
![]()

## Technical Details:
- Streamlined data processing by developing an ETL pipeline that successfully imported 35,737 search records and 7,823 host-guest interactions from TSV files, as measured by 100% data integrity in the resulting dataframes, by creating a flexible import function that adapts to various separator types.
- Identified key market segments by revealing that entire homes/apartments and private rooms were the most requested accommodation types, with acceptance rates of 42.49% and 43.46% respectively, as visualized in the "Acceptance Rate" chart in Tableau, providing insights for targeted property acquisition and management strategies.
- Uncovered global market reach by analyzing search patterns from 20+ countries, with the US (1,876 searches), Italy (1,625 searches), and Great Britain (1,457 searches) being the top origin countries, as displayed on an interactive world map in the dashboard.
- Optimized pricing strategy by establishing that the 400-500 price filter range had the highest acceptance rate of 48.55%, compared to the overall average of 42.78%, as measured by price range segmentation analysis visualized in the "Host Respond Time by Price Filter" chart.
- Enhanced understanding of booking preferences by determining that the average length of stay was 5.8 nights, with Saturday being the most popular check-in day (5.8 nights on average), as shown in the "Number of Nights by Check-in Day" chart.
- Revealed potential areas for improving conversion rates by identifying significant variations in booking success across countries, with the US having a 45.63% acceptance rate compared to India's 15.96%, as displayed in the "Top Countries by Search & Bottom Countries by Acceptance" table.
- Identified seasonal demand patterns by revealing that October had the highest number of check-ins, as visualized through the "Check-in by Month Distribution" chart in Tableau, providing insights for targeted marketing and capacity planning.
- Optimized data analysis workflow by engineering functions to automate SQL Server database creation and dataframe loading, enabling efficient multi-table queries and analyses, which facilitated the creation of a comprehensive Tableau dashboard integrating multiple data dimensions.
