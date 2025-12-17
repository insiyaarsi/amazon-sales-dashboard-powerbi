# Amazon Sales Dashboard - Power BI

An interactive sales analytics dashboard built in Power BI to analyze Amazon sales data across India. This project visualizes sales performance, geographical distribution, and order status tracking to provide actionable business insights.

![Dashboard Overview](images/dashboard-screenshot.png)

## Overview

This dashboard provides a comprehensive view of Amazon sales operations, featuring key metrics and visualizations that help identify sales trends, top-performing regions, and order fulfillment patterns. The analysis covers sales data from April 2022 to June 2022, tracking performance across multiple Indian cities and states.

## Key Features

- **Sales Metrics**: Real-time tracking of total sales (₹89.08M) and seller count (19.25K)
- **Geographic Analysis**: 
  - Sales breakdown by city (top 10 cities including Bengaluru, Hyderabad, Mumbai)
  - State-level performance comparison (Maharashtra, Karnataka, Tamil Nadu leading)
- **Order Status Tracking**: Comprehensive filtering system with 12 different order statuses from pending to delivered
- **Time Series Analysis**: Monthly sales units trend visualization showing seasonal patterns
- **Product Category Navigation**: Easy filtering through various product categories including clothing, accessories, and more

## Dataset

The analysis uses publicly available Amazon sales data that includes:
- Order details (order ID, date, status)
- Product information (category, size, quantity)
- Customer data (city, state)
- Sales figures and fulfillment details

**Data Source**: Public dataset containing Amazon India sales transactions

## Technical Details

**Tools Used**:
- Power BI Desktop for dashboard development
- DAX for calculated measures and metrics
- Power Query for data transformation

**Key Visualizations**:
- Horizontal bar charts for city and state comparisons
- Area chart for temporal trends
- Card visuals for KPI metrics
- Interactive slicers for dynamic filtering

## Insights

The dashboard reveals several interesting patterns:
- Bengaluru leads in city-wise sales with ₹8.2M, followed by Hyderabad (₹6.3M) and Mumbai (₹5.0M)
- Maharashtra is the top-performing state with ₹16M in sales
- Sales units show relatively stable performance with a notable peak in late May 2022
- The majority of orders are successfully delivered, though the dashboard allows filtering by various fulfillment stages

## Getting Started

### Prerequisites
- Power BI Desktop (latest version recommended)
- Windows 10 or later

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/insiyaarsi/amazon-sales-dashboard-powerbi.git
   ```

2. Download Power BI Desktop from [Microsoft's official website](https://powerbi.microsoft.com/desktop/) if you haven't already

3. Open the `.pbix` file in Power BI Desktop

4. The data source is embedded in the file, so you can immediately interact with the dashboard

### Usage

- Use the **Status** filter panel on the left to focus on specific order statuses
- Click on **product categories** in the left sidebar to drill down into specific product performance
- Toggle between **Sales** and **Units** views using the buttons in the top right
- Hover over visualizations for detailed tooltips and additional information

## Project Structure

```
amazon-sales-dashboard-powerbi/
├── Amazon Sales Dashboard.pbix    # Main Power BI dashboard file
├── data/                          # Data files
│   └── Amazon Sale Report.csv     # Source dataset
├── images/                        # Dashboard screenshots
│   └── dashboard-screenshot.png
└── README.md                      # Project documentation
```

## Future Enhancements

Potential improvements for this dashboard:
- Add year-over-year comparison analysis
- Include profitability metrics and margin analysis
- Implement predictive analytics for sales forecasting
- Add customer segmentation analysis
- Create mobile-optimized view

## License

This project is open source and available under the MIT License.

## Contact

Feel free to reach out if you have questions or suggestions for improvements!

---

**Note**: This dashboard was created for educational and analytical purposes. The data used is publicly available and does not contain any confidential information.
