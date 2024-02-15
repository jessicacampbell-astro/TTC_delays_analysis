# TTC Delays Analysis
The Toronto Transit Committee (TTC) operates Canada's most popular rapid transit system, with nearly 1 million people riding the subway on weekdays. I performed an exploratory analysis of their [subway delay data](https://open.toronto.ca/dataset/ttc-subway-delay-data/) using SQL and Tableau to investigate performance metrics, YoY KPIs, time-dependent trends, and pain points for presentation to cross-functional teams and to inform performance strategies.

## Summary of Insights

**Yearly trends:** The were a total of 21,799 delays during 2023 for a total delay time of 63,623 minutes and an average delay time of 3 minutes. While the number of delays has increased since 2022 (18,290), the total time spent during delays (66,891 minutes) and the average delay time (4 minutes) are lower. Most delays were 7 minutes or less and lasted as long as 360 minutes.

![delay_dist](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/9c9eac06-25cb-4d1f-b1b3-49213dff0e07)

**Pain points (stations):** The station with the greatest number of delays is Kennedy Station (Line 1) with 360 delays for a total delay time of 2,872 minutes. This is followed by Kipling Station (Line 2), Eglinton Station (Line 1), Finch Station (Line 1), and Bloor Station (Line 1).

![pain_points](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/09b15efb-d24b-4e31-99ec-496c87a01315)

**Pain points (codes):** The most frequent cause of delays was disorderly patrons (code SUDP), accounting for 6,970 delays for a total delay time of 18,398 minutes. This is a significant increase of SUDP codes since 2022, which experienced 3,800 such delays for a total delay time of 12,484 minutes.

![sudp](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/5c74ea73-960a-4f11-94cd-97657659cca8)

**Daily trends:** Most delays occur at 8 am, 5 pm, and 10 pm, likely due to increased ridership during rush-hour traffic. 

![daily_trends](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/9ed9e22f-46b8-43ac-b328-b2caba6e4a10)

**Seasonality:** While the number of delays does not significantly vary throughout the year, December and March have the most number of delays while January has the least.

![seasonality](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/2cddefd9-e673-4086-bb2f-f65724844052)



## Recommendations
