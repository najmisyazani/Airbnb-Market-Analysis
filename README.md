## Project Summary:
To analyze guest search patterns and host acceptance behaviors in the Dublin Airbnb market, aiming to identify gaps between guest demand and host supply, and provide actionable insights to increase bookings and improve market efficiency.

## Dashboard Overview:
![]()

## Technical Details:
- Streamlined data processing by developing an ETL pipeline that successfully imported 35,737 search records and 7,823 host-guest interactions from TSV files, as measured by 100% data integrity in the resulting dataframes, by creating a flexible import function that adapts to various separator types.
- Identified a mismatch in room supply by revealing that 2-guest bookings were most common despite 1-guest searches being more frequent, as measured by a comparative analysis of search and booking patterns using Python's pandas and seaborn libraries.
- Uncovered opportunities for market growth by determining that private rooms had the highest acceptance rate at 43.5%, as measured by room type segmentation analysis, visualized through bar plots in Python (Matplotlib).
- Enhanced understanding of booking conversion by establishing a 60% rate of accepted inquiries resulting in confirmed reservations, as measured by time series analysis of host-guest interactions, providing insights for improving the inquiry-to-booking process.
- Revealed potential cultural biases in the market by identifying that guests from India faced the lowest acceptance rate at 15%, half that of the next lowest country, as measured by country-wise acceptance rate analysis using pandas groupby operations.
- Optimized data analysis workflow by engineering a function to automate SQL Server database creation and dataframe loading, as measured by successful integration of three complex datasets (searches, contacts, and merged data) into a relational database structure, enabling efficient multi-table queries and analyses.
