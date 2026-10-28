# Marketing Analytics: Campaign Performance, Conversion Funnel & ROAS

## Project Overview

This project analyzes digital advertising performance using campaign, event, and customer-related data. It evaluates the customer conversion funnel, compares campaign and content performance, and examines advertising cost efficiency and revenue outcomes.

## Objectives

- Analyze user progression from impressions to clicks and purchases.
- Calculate campaign-level Click-Through Rate (CTR) and Conversion Rate (CVR).
- Compare advertising performance across content types and platforms.
- Calculate CPM, CPC, CPA, ROAS, and ARPPU.
- Identify campaigns and content combinations with strong conversion and revenue performance.
- Translate analytical results into actionable marketing recommendations.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Data Structure

The notebook uses event-level advertising data (`fact_ads`) and campaign dimension data (`dim_campaign`).

The event data includes fields such as event ID, ad ID, user ID, timestamp, event type, purchase revenue, gender, and age group. Campaign data provides advertising metadata and budget information.

## Analysis Workflow

1. Convert event timestamps to datetime.
2. Filter events for Impression, Click, and Purchase funnel analysis.
3. Aggregate unique users across funnel stages.
4. Calculate CTR and CVR for each campaign.
5. Compare performance by advertising platform and content type.
6. Combine revenue and budget information.
7. Calculate CPM, CPC, CPA, ROAS, and ARPPU.
8. Identify performance patterns and develop marketing recommendations.

## Key Metrics

- **CTR:** Clicks divided by impressions.
- **CVR:** Purchases divided by clicks.
- **CPM:** Advertising cost per 1,000 impressions.
- **CPC:** Advertising cost per click.
- **CPA:** Advertising cost per purchase or acquisition.
- **ROAS:** Attributed advertising revenue divided by advertising cost.
- **ARPPU:** Revenue divided by purchasing users.

## Analytical Considerations

- Funnel definitions should be consistent and based on clearly defined user events.
- Zero denominators should be handled when calculating rates and cost metrics.
- Revenue and budget aggregations should be checked for duplication after joins.
- ROAS interpretation depends on whether the cost field represents actual advertising spend or allocated budget.
- Recommendations should be supported by the calculated results.

## Learning Outcomes

This project demonstrates practical marketing analytics skills, including conversion funnel analysis, campaign evaluation, advertising cost metrics, revenue analysis, and data-driven marketing decision support.
