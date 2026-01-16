# Tableau Air BnB Analytics Dashboard

A comprehensive Tableau data visualization project that analyzes Airbnb listing data to uncover insights about pricing trends, revenue patterns, and geographic distribution across different markets.

## 📊 Dashboard Preview

![Tableau Air BnB Analytics Dashboard](Screenshot%202026-01-16%20135241.png)

The interactive dashboard provides multiple views of Airbnb data, enabling data-driven decision making for hosts, investors, and market analysts.

## ✨ Features & Insights

This Tableau workbook includes the following analytical visualizations:

### 1. **Revenue for Year**
- Time-series visualization showing revenue trends throughout the year
- Identifies seasonal patterns and peak earning periods
- Enables forecasting and revenue optimization strategies

### 2. **Average Price per Bedrooms**
- Bar chart displaying pricing variations based on bedroom count
- Shows clear pricing tiers from studios to multi-bedroom properties
- Reveals that 6-bedroom properties command the highest average price (~$643)

### 3. **Price per Zipcode (Geographic Map)**
- Interactive color-coded map visualization of pricing by zipcode
- Displays geographic concentration of listings
- Identifies premium and budget-friendly neighborhoods
- Zipcodes color-coded by price ranges (98101-98199)

### 4. **Price By Zipcode (Bar Chart)**
- Horizontal bar chart showing price distribution across different zipcodes
- Enables quick comparison of pricing across geographic areas
- Helps identify market opportunities and competitive positioning

### 5. **Distinct Count of Bedrooms**
- Distribution analysis showing inventory breakdown by bedroom count
- Reveals market composition (1 BR: 1,823 units, 2 BR: 1,353 units, etc.)
- Useful for understanding market supply and demand dynamics

## 📁 Project Structure

```
Tableau_Air_BnB/
├── Air BnB Full Project.twb          # Tableau workbook file (main dashboard)
├── Tableau Full Project.xlsx          # Source data file (~43.5 MB)
├── Screenshot 2026-01-16 135241.png  # Dashboard preview image
└── README.md                          # Project documentation (this file)
```

## 💾 Data Source

- **File**: `Tableau Full Project.xlsx`
- **Size**: 43.5 MB
- **Content**: Comprehensive Airbnb listing data including:
  - Property details (bedrooms, location, zipcode)
  - Pricing information
  - Revenue metrics
  - Temporal data for trend analysis

## 🚀 How to Use

### Prerequisites
- Tableau Desktop (or Tableau Reader for viewing only)
- Windows, macOS, or Linux operating system

### Opening the Dashboard

1. **Download the repository** or clone it to your local machine
2. **Open Tableau Desktop** (or Tableau Reader)
3. **Open the workbook**: 
   - File → Open → Select `Air BnB Full Project.twb`
4. **Interact with the visualizations**:
   - Click on map regions to filter data
   - Hover over charts for detailed tooltips
   - Use filter controls on the left panel
   - Switch between different dashboard sheets

### Data Refresh (Optional)
If you have Tableau Desktop and want to modify or refresh the data:
1. The workbook is connected to `Tableau Full Project.xlsx`
2. Ensure the Excel file is in the same directory
3. Refresh the data source if the Excel file is updated

## 📈 Key Insights from the Analysis

Based on the dashboard visualizations:

1. **Pricing Trends**: Clear correlation between bedroom count and pricing, with 6-bedroom properties commanding premium rates

2. **Geographic Variation**: Significant price differences across zipcodes, indicating neighborhood-based pricing strategies

3. **Market Composition**: The market is dominated by 1-2 bedroom properties (over 3,000 combined units), suggesting strong demand for smaller rentals

4. **Revenue Patterns**: Steady revenue growth visible throughout the year with some seasonal fluctuations

5. **Supply Distribution**: Balanced distribution across bedroom counts provides diverse inventory for different customer segments

## 🛠️ Technical Details

- **Tableau Version**: Compatible with Tableau Desktop/Reader
- **File Format**: `.twb` (Tableau Workbook)
- **Data Format**: `.xlsx` (Microsoft Excel)
- **Visualization Types**: Line charts, bar charts, geographic maps, tables
- **Interactivity**: Full filtering and drill-down capabilities

## 📝 Use Cases

This dashboard is valuable for:

- **Airbnb Hosts**: Optimize pricing strategies based on location and property size
- **Real Estate Investors**: Identify high-yield markets and property types
- **Market Analysts**: Understand competitive landscape and market dynamics
- **Data Analysts**: Learn Tableau visualization techniques for rental data

## 📄 License

This project is available for educational and analytical purposes.

---

**Created with**: Tableau Desktop  
**Data Analysis**: Airbnb Market Intelligence  
**Last Updated**: January 2026