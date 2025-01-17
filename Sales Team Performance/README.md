# Sales Team Performance Dashboard 

![Sales Team Performance Dashboard]([https://github.com/Shantydotcom/Google-Looker-Studio/blob/main/Orders%20Dashboard/Orders%20Dashboard.png]

This project analyzes and visualizes the performance of a sales team. It leverages Looker Studio and a Google Sheet as the data source to create an interactive dashboard with rich visual insights and key performance indicators (KPIs).

[View the interactive report](https://lookerstudio.google.com/u/0/reporting/fefea2f9-61cd-4eab-a9c6-c1bcc5a016cc/page/yutdE)


## Dashboard Features

### 1. Key Performance Indicators (KPIs)
- **Sales**: Total revenue generated.
- **Cost**: Calculated field as `Sales - Profit`.
- **Profit**: Net earnings after deducting costs.

### 2. Visual Insights
- **Combo Chart**: Displays monthly trends of sales and profit with dual-axis comparison.
- **Stacked Column Chart**: Highlights the distribution of cost and profit over months.
- **Pie Charts**: Breakdown of sales by product category and sales performance by salesperson.

### 3. Interactivity
- **Date Control**: Filter the dashboard by custom date ranges.
- **Category Filters**: Drill down by product categories, managers, and salespeople.

### 4. Tools and Technologies
- **Google Looker Studio**: For dashboard creation and data visualization.
- **Google Sheets**: Data source containing sales, profit, and other metrics.
- **Google Drive**: For storing and accessing the dataset.

### 5. Key Insights
- Monitor monthly sales and profit trends.
- Understand cost breakdown and profit margins by product categories.
- Evaluate individual salesperson and manager contributions to the overall performance.

### 6. Dataset
The dataset resides in a Google Sheet, with fields including:
- Sales
- Profit
- Manager
- Salesperson
- Product Category
- Month

## How to Use

### Set Up the Data Source:
1. Open Looker Studio and click on `Blank Report`.
2. Select `Google Sheets` as the data source.
3. Choose the file and sheet containing your sales data.

### Configure Page Settings:
1. Adjust the page size to fit your monitor. For wider monitors, select a wide resolution with lower height.

### Design the Layout:
1. Delete the default table created by Looker Studio.
2. Use text boxes for the dashboard title. Set a prominent font size and customize the border color to black.
3. Enable `Snap to Grid` from the View menu and adjust the grid size for precise alignment.

### Add Filters:
1. Insert a `Date Control` to filter data by date.
2. Place the date control at the top of the dashboard with a black border for a clean look.

### Create Calculated Fields:
1. Add a calculated field named `Cost` (`Sales - Profit`).
2. Save and confirm the calculated field addition.

### Add Visualizations:
1. **Scorecards**: Display metrics for sales, cost, and profit.
2. **Combo Chart**: Visualize sales and profit trends over time. Configure axes, dimensions, and metrics for clarity.
3. **Stacked Column Chart**: Show monthly profit and cost distribution.
4. **Pie Charts**: Analyze sales by product categories and salespeople.

### Finalize the Dashboard:
1. Switch to `View` mode to interact with the completed dashboard.
2. Share and analyze performance data with stakeholders.

