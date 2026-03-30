# Meta Ads Performance Analysis Dashboard

## Project Overview
This project is a Power BI dashboard designed to track and analyze the performance of advertising campaigns across Meta platforms, including Facebook and Instagram. It provides a complete view of campaign performance across the marketing funnel, from awareness to engagement to purchases, along with demographic, geographic, and time-based insights.

## Objective
The objective of this dashboard is to:
- Track key advertising KPIs
- Measure campaign effectiveness
- Understand audience engagement patterns
- Identify conversion bottlenecks
- Support better targeting and budget allocation decisions

## Tools & Techniques
- **Power BI** for dashboard development and visualization
- **DAX** for calculated measures and KPI logic
- **Data Modeling** for building table relationships
- **Star Schema** for organizing fact and dimension tables to support efficient analysis and better dashboard performance
- **CSV Files** as the source dataset

## Dataset Overview
The dataset includes:
- Campaign-level data
- Ad-level details
- User demographic information
- Ad event tracking data

### Data Model
This project follows a **star schema** structure:

- **Fact Table:** `ad_events`
- **Dimension Tables:** `ads`, `campaigns`, `users`

## KPI Metrics
The dashboard tracks the following key metrics:

- **Impressions:** 216K  
  Total number of times the ads were shown, indicating strong overall reach.

- **Clicks:** 25.4K  
  Number of users who clicked on the ads.

- **Shares:** 1.3K  
  Represents content amplification and audience interest beyond paid reach.

- **Comments:** 2.6K  
  Indicates user interaction and content engagement.

- **Purchases:** 1.3K  
  Total conversions generated through the campaigns.

- **Engagements:** 29K  
  Combined interaction count including clicks, likes, shares, and comments.

- **CTR (Click-Through Rate):** 11.76%  
  A very strong CTR, showing that the creatives and targeting are highly effective.

- **Engagement Rate:** 13.56%  
  Indicates healthy interaction levels and strong audience response.

- **Conversion Rate:** 5.21%  
  Percentage of clicks that converted into purchases.

- **Purchase Rate:** 0.61%  
  Percentage of total impressions that resulted in purchases.

- **Total Budget:** 2.5M  
  Total advertising spend across all campaigns.

- **Average Budget per Campaign:** 50.7K  
  Indicates the average campaign-level allocation.

## Dashboard Insights

### 1. Funnel Performance Analysis
The dashboard shows very strong top-of-funnel performance.
This indicates that while awareness and engagement are strong, purchase efficiency remains weak. The key improvement area lies in conversion optimization.

### 2. Engagement Breakdown
Engagement by Gender shows that female audiences engage more strongly than male audiences, suggesting an opportunity for more focused targeting.

#### By Age Group
- Peak engagement comes from the **20–30 age group**
- Engagement declines significantly after age 35

This suggests that the most responsive audience segment is **young adults**, particularly those aged **18–30**.

### 3. Geographic Distribution
This suggests campaigns should be optimized differently for:
- High-volume engagement markets
- High-value conversion markets

### 4. Time-Based Trends
#### Weekly Engagement Trend
- Engagement remains relatively consistent across weeks
- There are no sharp declines, indicating stable campaign performance over time

#### Hourly Engagement Trend
- Engagement peaks during the **late afternoon and evening**
- Lowest activity is seen in the **early morning hours (0–5 hours)**
This suggests ad delivery should be concentrated during afternoon and evening time slots for better results.

### 5. Calendar Analysis
The calendar view highlights noticeable engagement spikes on specific dates and 
These spikes may be linked to:
- Promotions
- Campaign launches
- Event-based activity
This suggests that event-driven campaigns and promotional timing have a strong influence on engagement.

### 6. Ad Type Performance
Performance by ad format shows:

- **Video ads** deliver the highest CTR, conversion rate, and engagement rate
- **Stories ads** also perform strongly, especially in reach and engagement
- **Image** and **Carousel** ads perform reasonably well, but slightly lower in conversion efficiency

This indicates that **Video** and **Stories** are the strongest-performing ad formats and should receive a larger share of the budget.

## Conclusion
The dashboard demonstrates strong campaign performance in visibility and engagement, but highlights a clear opportunity to improve purchase conversion efficiency. Future improvements should focus on conversion optimization, retargeting, and budget reallocation toward the most effective audiences, formats, and geographies.
