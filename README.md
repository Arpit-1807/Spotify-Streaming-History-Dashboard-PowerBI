# Spotify-Streaming-History-Analytics-Dashboard-PowerBI

1. **Project Overview**

This project analyzes a complete Spotify user streaming history dataset to uncover listening behavior patterns, engagement trends, and platform usage insights.

The dashboard transforms raw event-level streaming data (timestamps, tracks, artists, albums, play/skip reasons) into meaningful business-style KPIs and interactive visual analytics.

Built to simulate how a Data Analyst would extract insights from user engagement data in a real-world product environment.

2. **Business Objective**

To answer key behavioral and engagement questions:

~ How actively does the user consume music?

~ What are the most played tracks and artists?

~ Which songs are skipped most frequently?

~ What is the completion rate?

~ How does listening behavior vary monthly?

~ Which platforms are used most?

~ What patterns exist between play and skip behavior?

3. **Dataset Description**

The dataset includes:

~ Timestamp of streaming activity

~ Track name

~ Artist name

~ Album name

~ Listening duration (milliseconds)

~ Reason for start

~ Reason for end

~ Platform used (Android, iOS, Cast, etc.)

4. **Key KPIs Designed**	

| KPI                  | Description                           |
| -------------------- | ------------------------------------- |
| Tracks Played        | Total streams                         |
| Artists Played       | Unique artists listened               |
| Albums Played        | Unique albums consumed                |
| Total Listening Time | Overall engagement time (minutes)     |
| Skip Rate            | % of tracks skipped before completion |
| Completion Rate      | % of tracks played fully              |
| Most Used Platform   | Device-level engagement analysis      |

5. **Dashboard Highlights**

~ Most Played Tracks by Minutes

Identifies long-duration engagement tracks rather than just frequency.

~ Most Skipped Tracks

Helps understand low-retention songs.

~ Most Played Artists

Reveals loyalty patterns and artist preference depth.

~ Monthly Listening Trend

Shows seasonal engagement patterns and listening spikes.

~ Platform Usage Distribution

Analyzes device preference and consumption behavior.

6. **Key Insights Derived**

~ High completion rate (~94%) indicates strong listening intent.

~ Skip rate (~5%) suggests selective listening behavior.

~ Listening activity shows peak engagement in later months.

~ Android dominates platform usage, indicating device preference.

~ Certain tracks show high playtime but moderate skip frequency, indicating replay value.

7. **Tools & Technologies**

~ Power BI

~ Data Modeling

~ DAX Measures

~ Data Cleaning & Transformation

~ KPI Design

~ Time-Series Analysis

~ Behavioral Analytics

8. **Data Processing Steps**

8.1 Cleaned timestamp fields and standardized date formats

8.2 Converted listening duration from milliseconds to minutes

8.3 Created calculated measures for:

~ Skip Rate

~ Completion Rate

~ Total Listening Time

8.4 Built time-based hierarchy (Year → Month)

8.5 Designed interactive filters and slicers

9. **Dashboard Preview**

<img width="2048" height="1166" alt="image" src="https://github.com/user-attachments/assets/ca6294bb-e988-4452-b4e8-f37136217c11" />

10. **Business Value Simulation**

This project simulates how streaming platforms analyze:

~ User retention behavior

~ Engagement intensity

~ Content performance

~ Device-level usage patterns

~ Time-based activity cycles

11. **Future Enhancements**

~ Cohort-based listening analysis

~ Genre-based segmentation

~ Listening time distribution heatmaps

~ Predictive skip probability modeling (Python integration)

~ Recommendation pattern analysis
