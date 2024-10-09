# Kickstarter Campaign Analysis

## Overview
This project analyzes Kickstarter campaign data, focusing on campaign success rates, backers, and funding patterns. The data was sourced from a Kickstarter dataset and cleaned to ensure consistency, with additional calculated fields like goal range, funded percentage, and reward levels. The goal of the project is to provide insights into the factors influencing campaign success, including the best time to launch, categories with the highest success rates, and backer trends.

## Project Details

### 1. Data Cleaning and Transformation
- Cleaned the dataset to remove duplicates, fix data inconsistencies, and ensure uniform formatting across columns (e.g., name, category, subcategory).
- Created new fields such as `goal range`, `funded percentage`, and `reward levels` for better analysis.
- Transformed data fields like `funded date` into readable formats (e.g., `yyyy-mm-dd`).

### 2. Visualization 1: Duration Histogram
- Built a histogram to display the distribution of campaign durations.
- This provides insights into which durations are more likely to succeed.

### 3. Visualization 2: Histogram of Backers
- Created a histogram to visualize the number of backers across campaigns.
- This shows trends in backer engagement and which campaigns tend to attract more backers.

### 4. Visualization 3: Success Rates by Campaign Length
- Analyzed the success rates based on campaign length.
- This visualization helps identify the optimal campaign length for successful funding.

### 5. Visualization 4: Success Rate by Pledge Goal Range
- Created a visualization showing success rates based on pledge goal ranges.
- This gives insights into which goal amounts are more likely to be funded.

### 6. Visualization 5: Top Performing Categories by Success Rate
- Visualized success rates across different Kickstarter categories (e.g., Art, Technology).
- Identifies which categories are more likely to have successful campaigns.

### 7. Dashboard Creation
- Combined all visualizations into a cohesive, interactive dashboard for a comprehensive analysis.
- Applied filters like `goal range`, `backers`, and `duration` to enable dynamic exploration of the data.

## Tools Used
- **Google Sheets**: Used for data cleaning, pivot tables, and histogram creation.
- **Pivot Tables**: For summarizing and analyzing campaign success rates.
- **Histograms and Charts**: Used for visualizing backers, success rates, and campaign durations.

## Visualizations Included
- **Duration Histogram**: Displaying the distribution of campaign durations.
- **Backers Histogram**: Showing the number of backers across campaigns.
- **Success Rates by Campaign Length**: Analyzing the impact of campaign length on success.
- **Success Rate by Pledge Goal Range**: Insights into which goal ranges are most successful.
- **Top Performing Categories by Success Rate**: Visualizing the success rates across different Kickstarter categories.

## How to Use
1. **Google Sheets Link**: Open the Google Sheets file to explore the pivot tables and visualizations.
2. **Apply Filters**: Use filters like `goal range`, `backers`, and `duration` to customize the analysis.
3. **Explore the Dashboard**: Interact with the dashboard to discover trends in Kickstarter campaigns, including factors affecting campaign success.

## Future Improvements
- Add additional filtering options for more granular analysis (e.g., reward level, region).
- Expand the dataset to include more recent Kickstarter campaigns for updated insights.
