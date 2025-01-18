# Product Analysis Dashboard

![Sales Team Performance Dashboard](https://github.com/Shantydotcom/Google-Looker-Studio/blob/main/Sales%20Team%20Performance/Sales%20Team%20Performance.png)

This project demonstrates how to design a customizable dashboard using Google Looker Studio. It focuses on creating headers, KPIs, and visual insights through charts and interactive features.

[View the interactive report](https://lookerstudio.google.com/u/0/reporting/fefea2f9-61cd-4eab-a9c6-c1bcc5a016cc/page/yutdE)


## Dashboard Features
### 1. Key Performance Indicators (KPIs)
- Display key metrics such as total # of orders, total # of segments, total # of products, total sales, and total profit using Scorecards.
- Customized styles, colors, and decimal precision for better visibility.
- Use of compact numbers for clean, professional displays.

### 2. Visual Insights
- Donut Chart: Showcases percentage of total product sales by region with customized colors and shadows.
- Stacked Bar Chart: Highlight product sales by subcategory by top 10 values.
- Line Chart: Visualize total quantity trends for subcategories.

### 3. Interactivity
- Enabled dynamic updates for metrics and charts.
- Customized layout and background colors for seamless integration.
- Added borders and shadows for enhanced chart aesthetics.

### 4. Tools and Technologies
- Google Looker Studio: Primary dashboard creation tool.
- Custom Styling Options: Background colors, grid adjustments, and chart borders.
- Icons and Images: Utilized external resources to add icons for better visualization.

### 5. Key Insights
- Total number of orders and regional sales distribution.
- Top-selling subcategories by method of shipment.
- Quantity trends across subcategories.

### 6. Data Set
Sample fields include:
- Order ID: Unique identifier for orders.
- Sales: Total sales amount.
- Region: Geographical sales region.
- Subcategory: Product subcategories.

## How to Use

### Step 1: Customize the Background
- Navigate to Theme and Layout in Google Looker Studio.
- Select a theme and click Customize.
- Modify the background color under the Report Background section.

### Step 2: Build the Header
- Add a Text Box for the title:
- Set font size to 48, style to bold.
- Title: "Product Analysis".
- Insert a Line below the title and adjust the thickness to 3.

### Step 3: Add KPIs and Images
- Insert a separator Line to structure sections.
- Add KPI cards using Add Chart → Scorecard:
- Metric: Order ID, Segments, Product ID, Sales, Profit
- Style: Compact numbers with zero decimal places.
- Upload icons or images using the Upload from Computer option.

### Step 4: Create Charts
Donut Chart:
- Add a Donut Chart via Add Chart.
- Dimension: Region, Metric: Sales.
- Customize colors and add shadows for visual appeal.
  
Stacked Bar Chart:
- Insert a Stacked Bar Chart from Add Chart.
- Dimension: Subcategory, Metrics: Sales, Ship Mode.
- Limit chart to Top 10 Values and remove gridlines for clarity.
  
Line Chart:
- Add a Line Chart from Add Chart.
- Dimension: Subcategory, Metric: Quantity.
- Customize styles and add shadows to enhance the presentation.

### Step 5: Finalize the Dashboard
- Add titles to all charts for clarity.
- Adjust placements and alignments for a professional finish.

### Finalize the Dashboard:
1. Switch to `View` mode to interact with the completed dashboard.
2. Share and analyze performance data with stakeholders.
