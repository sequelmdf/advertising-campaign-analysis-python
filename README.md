# Advertising Campaign Performance Analysis

This project analyzes a synthetic advertising campaign dataset using Python, Pandas, and Matplotlib in Google Colab.

The dataset includes campaign performance across Google Ads, Meta Ads, and TikTok Ads, with metrics such as impressions, clicks, ad spend, conversions, revenue, ROAS, CPA, CTR, and CPC.

The goal of the project was to compare performance by platform, campaign type, industry, country, and platform-campaign combinations to identify the strongest returns, lowest costs, and most efficient advertising strategies.

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

## Dataset

The project uses the Global Ads Performance dataset from Kaggle, a synthetic dataset created for marketing analytics practice.

The dataset contains campaign-level performance across:

- Google Ads
- Meta Ads
- TikTok Ads

It includes 1,800 rows and 14 columns, with no missing values.

## Metrics Used

- Return on Ad Spend (ROAS)
- Cost Per Acquisition (CPA)
- Click-Through Rate (CTR)
- Cost Per Click (CPC)
- Ad Spend
- Revenue
- Conversions
- Impressions
- Clicks

## Business Questions

- Which advertising platform generated the strongest return on ad spend?
- Which platform generated conversions at the lowest cost?
- Which campaign type had the strongest average ROAS?
- Which industries performed most efficiently?
- Which countries generated the strongest return on ad spend?
- How did ad spend relate to revenue?
- Which platform and campaign-type combinations performed best?

## Analysis

Pandas was used to load, inspect, group, and summarize the advertising dataset.

Performance was analyzed across:

- Advertising platform
- Campaign type
- Industry
- Country
- Platform and campaign-type combinations

For each grouping, the analysis calculated:

- Total ad spend
- Total revenue
- Total conversions
- Average ROAS
- Average CPA
- Average CTR
- Average CPC

Matplotlib was used to create visualizations comparing campaign performance and advertising efficiency.

## Key Visuals

### Platform Performance Summary

![Platform Performance Summary](images/platform_performance_summary.png)

Google Ads generated the highest total revenue and conversions, but it also had the lowest average ROAS and highest average CPA. TikTok Ads showed stronger overall efficiency.

### Average ROAS by Platform

![Average ROAS by Platform](images/average-roas-by-platform.png)

TikTok Ads had the highest average ROAS, followed by Meta Ads and Google Ads.

### Average CPA by Platform

![Average CPA by Platform](images/average-cpa-by-platform.png)

TikTok Ads had the lowest average CPA, while Google Ads had the highest.

### Average ROAS by Campaign Type

![Average ROAS by Campaign Type](images/average-roas-by-campaign-type.png)

Search campaigns produced the highest average ROAS, followed by Display, Video, and Shopping campaigns.

### Ad Spend vs Revenue

![Ad Spend vs Revenue](images/ad-spend-vs-revenue.png)

Higher ad spend was sometimes associated with higher revenue, but the relationship was not consistent across campaigns.

### Top Platform-Campaign Combinations by ROAS

![Top Platform-Campaign Combinations by ROAS](images/top-platform-campaign-combinations-by-roas.png)

TikTok Search had the highest average ROAS, and TikTok campaigns accounted for four of the top six platform-campaign combinations.

## Key Findings

- TikTok Ads had the highest average ROAS at approximately 9.54, followed by Meta Ads at 6.92 and Google Ads at 4.11.
- TikTok Ads also had the lowest average CPA at approximately $29.20, making it the most cost-efficient platform for generating conversions.
- Google Ads generated the highest total revenue and total conversions, with approximately $22.0 million in revenue and 131,098 conversions, but it also had the lowest average ROAS and highest average CPA among the three platforms.
- Search campaigns had the highest average ROAS by campaign type at approximately 7.00, followed by Display, Video, and Shopping.
- EdTech had the highest average ROAS by industry at approximately 6.83, followed by SaaS and Healthcare.
- The UAE had the highest average ROAS by country at approximately 6.96, followed by Germany, Australia, and India. The USA had the lowest average ROAS among the countries analyzed.
- Ad spend and revenue showed a generally positive relationship, but higher spending did not consistently produce the highest revenue. This demonstrates why efficiency metrics such as ROAS and CPA are important when evaluating advertising performance.
- TikTok Search had the highest average ROAS among platform-campaign combinations at approximately 10.52, followed by TikTok Display and TikTok Video.
- TikTok Ads occupied the top four platform-campaign combinations by average ROAS, while Meta Display and Meta Search also appeared in the top six.
- Google Ads did not appear among the top six platform-campaign combinations by average ROAS, suggesting lower efficiency relative to TikTok and Meta in this dataset.

## Files

- `Advertising_Campaign_Performance_Analysis.ipynb` — Google Colab notebook containing the Python analysis, visualizations, and findings
- `global_ads_performance_dataset.csv` — dataset used for the analysis

## Recommendations

Based on the analysis, future advertising strategy should prioritize TikTok Ads, particularly TikTok Search and TikTok Display campaigns, because they generated the strongest returns and lower acquisition costs.

Google Ads should still be considered for scale because it generated the highest total revenue and conversions, but its efficiency should be reviewed. Possible opportunities include improving audience targeting, shifting budget toward stronger campaigns, and testing more engaging ad content.

## Project Goal

The goal of this project was to demonstrate how Python and Pandas can be used to analyze multi-platform advertising performance, compare marketing efficiency across multiple dimensions, and translate campaign data into actionable business insights.
