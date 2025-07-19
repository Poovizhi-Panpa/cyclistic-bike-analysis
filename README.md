# Cyclistic Bike-Share Analysis

This project analyzes 12 months of trip data from the Cyclistic bike-share program in Chicago to uncover trends in user behavior and provide actionable business recommendations. It was completed as part of a portfolio-building initiative to explore real-world data and communicate insights through both code and visuals.

## Project Structure

- `Cyclistic Analysis.ipynb` — Full notebook (from Jupyter)

## Business Task

The goal of this analysis is to help Cyclistic’s marketing team convert casual riders into annual members by understanding how these two rider types differ.


## Key Questions

- How do annual members and casual riders use Cyclistic bikes differently?
- When do they ride? What kind of bikes do they prefer?
- Can we design targeted marketing strategies to encourage casual riders to convert?


## Data Cleaning & Transformation Highlights

- Removed invalid records (e.g., rides with end time before start time)
- Converted timestamps into features like `month`, `hour`, `day_of_week`
- Created `ride_duration` and calculated ride `distance` using Haversine formula
- Normalized inconsistent GPS noise in station coordinates


## Exploratory Data Analysis (EDA)

Visualizations were created using `seaborn` and `matplotlib` to explore:

- Distribution of ride durations and distances by rider type
- Ride frequency across weekdays and hours
- Seasonal patterns and time-of-day trends
- Differences in bike type usage


## Key Insights

- Casual riders prefer riding in summer months and midday hours, especially on weekends.
- Members ride more consistently throughout the year, peaking during weekday commute hours.
- Classic bikes are preferred by both rider types.
- Casuals tend to take longer and slightly farther rides, indicating leisure usage.


## Recommendations

1. **Segment Users into Leisure vs. Commuter Packages**
   - Offer membership options with benefits tailored for leisure riders (e.g., museum passes, food discounts).

2. **Time-Based Campaigns**
   - Promote membership benefits during summer months and weekends — peak casual usage times.
   - Highlight time savings and convenience during commuting hours for potential members.

3. **Feature Classic Bikes in Promotions**
   - Most users prefer classic bikes — use them in marketing imagery.

4. **Encourage Longer-Term Membership**
   - Offer incentives for rides over 10 minutes to nudge casuals toward subscribing.


## Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- GitHub Pages (for hosting)
