# 2025-Smartphone-Analysis

I. Overview

This PowerBI dashboard aims to analyze a comprehensive dataset containing information about smartphone companies, models, their prices, release years, and technical specifications. The dashboard provides insights regarding year over year trends in smartphone pricing within the United States, as well as hardware trends in relation to prices to hopefully provide meaningful information to both consumers and companies within the industry.



II. Dataset Discussion

The dataset used in this project was found on kaggle.com here: https://www.kaggle.com/datasets/abdulmalik1518/mobiles-dataset-2025, and was accessed in March of 2025.

The dataset includes specifications and official launch prices of various mobile phone models from different manufacturers, with the following key features:

- Company/Brand Name

- Model Name

- Device specifications (Weight, RAM, Front/Back Camera resolution, Processor, Battery capacity, Screen size)

- Official launch prices across five countries (Pakistan, India, China, USA, Dubai)

- Launch year

III. Data Cleaning and Preprocessing 

The data was cleaned and processed initially in Python, using Pandas and Matplotlib. Numerical columns in the initial CSV file were presented as strings, which were converted to their proper datatypes before
visualization in PowerBI. Additionally, vague and missing values were removed from the dataset, as well as severe outliers.

IV. PowerBI Dashboard 

![Dashboard Preview 1](PowerBI-Pricing.png)



![Dashboard Preview 2](PowerBI-Specs.png)


This dashboard demonstrates the relationship between smartphone specifications and pricing in the US market. This page features:

- Price-to-RAM Ratio Analysis: The scatter plot in the top-left corner visualizes how US launch prices correlate with RAM capacity, revealing the premium consumers pay for additional memory.

- Brand Selection Filter: Interactive company filter which allows users to isolate and compare specific manufacturers' pricing and specification strategies.

- Time Range Slider: Enables analysis across different launch years (2014-2025), helping identify market trends over time.

- RAM Evolution Chart: The line graph on the bottom-left tracks the average RAM capacity in smartphones over time, showing the steady increase in memory specifications through time.

- Battery Capacity Trends: The bottom-right visualization shows how battery capacity has evolved over the years, indicating periods of significant improvement as well as plateaus.

