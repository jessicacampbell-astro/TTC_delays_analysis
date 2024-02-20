# TTC Subway Delays Analysis
The Toronto Transit Committee (TTC) operates Canada's most popular rapid transit system, with nearly 1 million weekday riders. I performed an exploratory analysis of their [subway delay data](https://open.toronto.ca/dataset/ttc-subway-delay-data/) using SQL and Tableau to investigate performance metrics, YoY KPIs, time-dependent trends, and pain points for presentation to cross-functional teams and to inform performance strategies.

## Interactive Tableau Dashboard

![tableau-dashboard](https://github.com/jessicacampbell-astro/TTC_transportation_analysis/assets/23153120/55e6b251-e82d-4b27-a6a9-44d071351e5a)

There were 21,799 delays in 2023 with an average delay time of 3 minutes. While the number of delays is up by 19% since 2022, the average delay time is down by 20%. The delay times for 2023 range from 2 minutes (no change since 2022) to 360 minutes (down 7%), with a standard deviation of 8 minutes (down 27%). Disorderly patrons were by far the leading cause of delays, accounting for nearly 70% of delays in 2023, with 10-30% monthly increases since 2022.

## Summary of Insights

**Yearly trends:** There were 21,799 delays in 2023 for a total delay time of 63,623 minutes and an average delay time of 3 minutes. While the number of delays has increased since 2022 (18,290), the total time spent during delays (66,891 minutes) and the average delay time (4 minutes) are lower. Most delays were 7 minutes or less and lasted as long as 360 minutes.

![delay_dist](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/9c9eac06-25cb-4d1f-b1b3-49213dff0e07)

**Pain points (stations):** The station with the greatest number of delays is Kennedy Station with 360 delays for a total delay time of 2,872 minutes. This is followed by Kipling Station (299 delays for 1,794 minutes), Eglinton Station (272 delays for 1,962 minutes), Finch Station (265 delays for 1,614 minutes), and Bloor Station (Line 1; 224 delays for 1,861 minutes).

![pain_points](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/09b15efb-d24b-4e31-99ec-496c87a01315)

**Pain points (codes):** The most frequent cause of delays was disorderly patrons (code SUDP), accounting for 6,970 delays for a total delay time of 18,398 minutes. This is a significant increase in SUDP codes since 2022, which experienced 3,800 such delays for a total delay time of 12,484 minutes.

![sudp](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/5c74ea73-960a-4f11-94cd-97657659cca8)

**Daily trends:** Most delays occurred at 8 am (1,102 delays), 5 pm (1,323 delays), and 10 pm (1,284 delays), likely due to increased ridership during rush-hour traffic. 

![daily_trends](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/9ed9e22f-46b8-43ac-b328-b2caba6e4a10)

**Seasonality:** The number of delays does not significantly vary throughout the year, ranging from 1,635 to 2,009 monthly delays. December (2,009 delays) and March (1,985 delays) had the highest number of delays while January (1,635) had the least.

![seasonality](https://github.com/jessicacampbell-astro/TTC_delays_analysis/assets/23153120/2cddefd9-e673-4086-bb2f-f65724844052)

**Performance metrics:** While Kennedy Station had the highest number of delays in 2023 (2.9 million), it saw a drastic 32% reduction in the number of delays since 2022. The worst 5 subway stations in terms of the number of delays all saw improvements since the previous year, except St. George Station on Line 1 which saw a 1% increase. 

![delay_change](https://github.com/jessicacampbell-astro/TTC_transportation_analysis/assets/23153120/0f359958-8efd-4d2d-b43a-bca7cad682ee)

## Recommendations

The team provides the following recommendations: 

- Investigate the unusually long delay times (particularly those approaching 360 minutes) as well as the stations most impacted by delays (Kennedy, Kipling, Eglinton, Finch, and Bloor Line 1) to improve performance and ridership experience.
-  Refine the ambiguous description of 'disorderly patron' to help guide future research and improve upon campaigns that inform the public on how riders are affecting delays, with a focus on Bloor Station on Line 1.
- Focus delay improvement efforts on times when delays are the highest, including the hours of morning and evening rush hour and throughout March and December.
- Investigate why St. George Station on Line 1 has shown no improvement in delays since 2022, in light of being among the worst 5 stations.
- Validate the delays that occurred outside of operational times.


