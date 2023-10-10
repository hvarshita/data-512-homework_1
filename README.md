# DATA 512: Human Centered Data Science

## Summary:
The goal of this assignment is to construct, analyze, and publish a dataset of monthly article traffic for a select set of pages from English Wikipedia from July 1, 2015 through September 30, 2023. The primary focus is on incorporating the best practices for reproducibility and openness, as outlined in "[Assessing Reproducibility](http://www.practicereproducibleresearch.org/core-chapters/2-assessment.html)" and "[The Basic Reproducible Workflow Template](http://www.practicereproducibleresearch.org/core-chapters/3-basic.html)". 

## Data Source:
To gather the necessary data, the project utilizes the Pageviews Wikipedia API to make requests for pageview counts. 
1. [Pageviews API](https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)
2. [Pageviews Documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews)

* [Wikimedia Foundation REST API terms of use](https://www.mediawiki.org/wiki/API:REST_API#Terms_and_conditions)

## Required Libraries:
matplotlib
urlib
requests
json
time

## Repository Structure:
├── 
│   ├── hcds_data_acquisition_analysis.ipynb
├── data
│   ├── academy_monthly_cumulative_201507-202309.json
│   ├── academy_monthly_desktop_201507-202309.json
│   ├── academy_monthly_mobile_201507-202309.json
│   ├── thank_the_academy.AUG.2023.csv.xlsx
├── images
│   ├── fewest_months_data.png
│   ├── min_max_avg.png
│   ├── top_10_peak_page_views.png
├── LICENSE
├── README.md





