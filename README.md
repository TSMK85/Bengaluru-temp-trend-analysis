🌡️ Bengaluru Temperature Trend Analysis (Descriptive Analytics)

This project explores long-term climate trends in Bengaluru through daily temperature data. Using Excel as the core tool, it applies principles of descriptive statistics, data cleaning, and visualization to uncover shifts in annual average temperatures and long-term patterns through a 10-year moving average.

📁 Project Overview

- Type: Descriptive Analytics
- Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting)
- Focus: Climate trend analysis based on temperature data
- Time Frame: 1960 – 2024
- Key Outputs: Annual average temperatures, 10-year moving average (MAVG), and trendline visualization

🛠️ Data Processing & Analysis Steps

1. Removed Irrelevant Columns  
   - Dropped the "Rain Probability" column to focus strictly on temperature-based analysis.

2. Formatted as an Excel Table  
   - Enabled structured referencing and enhanced readability.

3. Cleaned and Standardized Data  
   - Rounded Max/Min temperature values to two decimal places.
   - Handled most missing values via interpolation, remaining shall be rigorously tended to in next the phase

4. Created Derived Columns  
   - `Avg Temp`: Computed as the mean of Max and Min temp  
     `= (Temp Max + Temp Min) / 2`  
   - `Year`: Extracted from the date field for time-based aggregation.

5. Generated Pivot Table  
   - Grouped by Year and calculated the average of daily Avg Temp.

6. Added 10-Year Moving Average (MAVG)  
   - Smoothed the annual average series to reveal long-term climate trends.

7. Visualized the Data  
   - Plotted both the raw annual averages and MAVG as line charts.
   - Added linear trendlines with axis labels, legend, and titles for clarity.

📊 Sample Outputs

- 📈 Annual Avg Temp Line Chart
- 🔁 10-Year MAVG overlay
- 📉 Linear trendline showing temperature shift
- 📍 Notable warmest year: 2023

Visuals available in the `Charts` folder.

📌 Key Insights

- The dataset shows a consistent warming trend post-1980s.
- 2023 was observed as the warmest year in the dataset.
- The 10-year MAVG highlights a smoothed trajectory of increasing temperatures across six decades.

---------------END---------------

