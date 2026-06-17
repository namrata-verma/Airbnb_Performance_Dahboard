# Airbnb Performance Dashboard

## Overview

This repository contains an analytics pipeline and performance dashboard for Airbnb marketplace data. It is designed to extract operational and strategic insights from listings, reviews, pricing, host trust, and guest engagement.

The project focuses on transforming raw data into a production-ready analytics model and visualization layer that supports decision-making for growth, pricing, and trust metrics.

## Data Model

The model is built on three core entity sets:

### Listings
- `listing_id`
- `city`
- `property_type`
- `price`
- `host_id`

### Hosts
- `host_id`
- `verification_status`
- `superhost_flag`
- `profile_attributes`

### Reviews
- `review_id`
- `listing_id`
- `review_date`
- `rating_metrics`
- `reviewer_id`

## Analytical Dimensions

- Platform growth and time-series listing trends
- City-level market concentration
- Price segmentation by property type
- Review frequency and satisfaction distribution
- Host verification and trust signal analysis
- Guest engagement and review behavior

## Key Insights

- Listing growth patterns reflect regulatory cycles and macro disruptions like COVID-19.
- Activity is concentrated in top cities, with major hubs driving a disproportionate share of listings and reviews.
- Pricing varies significantly across accommodation types, with full units and hotels commanding premium rates.
- Ratings are consistently strong, indicating high platform satisfaction in cleanliness, communication, and location.
- Most guests submit only one review, highlighting the need for stronger retention and repeat engagement strategies.
- Host verification and trust indicators are widely adopted, reinforcing platform credibility.

## Dashboard Features

- City-level performance monitoring
- Time-series growth and review trend analysis
- Property type and pricing segmentation
- Review count and guest engagement dashboards
- Host verification and trust metrics
- Multi-attribute rating analysis

## Business Value

This dashboard enables stakeholders to:

- Identify high-potential and underpenetrated markets
- Optimize pricing strategy by property category
- Monitor guest satisfaction and service quality
- Understand host trust and verification health
- Anticipate market shifts from external events

## Usage

1. Load the Airbnb dataset into your Python or BI environment.
2. Run data ingestion, cleaning, and normalization routines.
3. Build aggregated tables for listings, reviews, and host indicators.
4. Connect the processed datasets to the dashboard visualization layer.
5. Use filters by city, property type, and time range to explore insights.
6. Export KPI summaries and visual reports for stakeholders.

## Next Steps

- Add predictive demand forecasting
- Build price optimization models
- Segment guests by behavior and lifetime value
- Add geospatial clustering for location-based analysis
- Integrate streaming or real-time data sources for live dashboards


