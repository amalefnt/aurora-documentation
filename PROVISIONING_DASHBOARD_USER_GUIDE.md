# Aurora Provisioning Dashboard - User Guide

## 📊 Overview

The Provisioning Dashboard provides real-time insights into the provisioning team's performance, workload distribution, and completion metrics. This guide explains what each chart shows and how to interpret the data.

---

## 🎯 Dashboard Layout

The Provisioning Dashboard is organized into 5 main sections:

1. **Orders in Provisioning Stage** - Current workload overview
2. **Provisioning Completion** - Team performance by provisioner
3. **Provisioning Completion by Group Type** - Work distribution analysis
4. **Abnormal Orders** - Data quality indicators
5. **Provisioner Performance** - Individual performance trends

---

## 📈 Chart-by-Chart Guide

### 1. Orders in Provisioning Stage (Top Bar Chart)

**What it Shows:**
- Number of orders currently in the provisioning stage
- Data broken down by month for the selected time period
- Default view: Last 12 months or current financial year

**How to Read:**
- **X-axis**: Months (most recent on the left)
- **Y-axis**: Number of orders
- **Bars**: Each bar represents the count of orders in provisioning for that month
- **Total Count**: Displayed prominently next to the title

**What to Look For:**
- **Trends**: Are orders increasing or decreasing over time?
- **Spikes**: Unusual high volumes that might indicate bottlenecks
- **Seasonal Patterns**: Regular patterns in workload

**Actions You Can Take:**
- Click any bar to download detailed data for that month
- Use the dropdown to switch between "Last 12 Months" and "This Financial Year"
- Click the download icon to export all data

---

### 2. Provisioning Completion (Left Table)

**What it Shows:**
- Performance of individual provisioners for the selected date range
- Business Unit (BU) values achieved by each provisioner
- Optional: Provisioning values (monetary) - only visible to authorized users

**How to Read:**
- **Provisioner Column**: Names of team members, ranked by performance
- **BU Column**: Business Unit value completed (higher = better performance)
- **Provisioning Value**: Dollar value of completed work (if shown)
- **Total**: Summary row showing overall team performance

**Key Metrics:**
- **BU (Business Unit)**: Standardized measure of work completed
- **Ranking**: Provisioners automatically sorted by BU value (highest first)
- **Performance Indicators**: 
  - Top performers appear at the top
  - Consistent performers maintain steady BU values
  - New team members may show lower values initially

**Actions You Can Take:**
- Click download icon next to any provisioner to get their detailed orders
- Click "..." icon to view/edit additional BU assignments (admin only)
- Download total data using the main download button

---

### 3. Provisioning Completion by Group Type (Right Pie Chart)

**What it Shows:**
- Distribution of completed provisioning work across different service types
- Percentage breakdown of work by group type
- Visual representation of team focus areas

**How to Read:**
- **Pie Slices**: Each slice represents a different group type
- **Size**: Larger slices = more work completed in that category
- **Percentages**: Shown inside slices (only displayed if >5% of total)
- **Tooltip**: Hover for exact counts and percentages

**Common Group Types:**
- **Regular**: Standard telecommunications services
- **Group 4**: Specialized mobile network services
- **NBN**: National Broadband Network services
- **Custom**: Bespoke solutions

**What to Look For:**
- **Balanced Distribution**: Healthy mix across service types
- **Specialization**: High concentration in specific areas
- **Market Trends**: Shifts in service demand over time

**Actions You Can Take:**
- Click any slice to download orders for that specific group type
- Use the toolbox (top right) to save the chart as an image

---

### 4. Abnormal Orders (Right Bottom Panel)

**What it Shows:**
- Data quality indicators highlighting orders with missing or incorrect information
- Count of orders that need attention before they can be processed properly

**Categories Explained:**

**🚨 Abnormal Orders (Total)**
- Orders that have one or more data quality issues
- This is the sum of all specific abnormalities below

**📊 Specific Abnormalities:**

**Empty Group Type**
- Orders without a specified service type
- **Impact**: Cannot be properly categorized or priced
- **Action Needed**: Assign appropriate group type

**Empty Provisioner**
- Orders not assigned to any team member
- **Impact**: Work cannot be tracked or managed
- **Action Needed**: Assign to appropriate provisioner

**Empty Work Type**
- Orders missing work classification
- **Impact**: Cannot determine required skills or resources
- **Action Needed**: Specify the type of work required

**Service Price Not Found**
- Orders where pricing information is missing from the system
- **Impact**: Cannot calculate revenue or costs
- **Action Needed**: Update pricing database or contact commercial team

**What to Look For:**
- **Zero Abnormal Orders**: Ideal state - all data is complete
- **High Abnormal Count**: Indicates data quality issues need attention
- **Trending Increases**: May indicate process problems or training needs

**Actions You Can Take:**
- Click any category to download the specific abnormal orders
- Use this data to follow up with order creators or data entry teams
- Track improvements over time

---

### 5. Provisioner Performance (Bottom Chart)

**What it Shows:**
- Individual provisioner performance trends over time
- Comparison of work completion (BU values) across multiple time periods
- Optional: Financial performance including costs and provisioning values

**Controls:**
- **Time Period**: Choose "This Financial Year" or "Last 12 Months"
- **View Type**: Select "Monthly" or "Weekly" data granularity
- **Provisioner**: Select individual team member to analyze

**Chart Elements:**

**Blue Bars - BU Value**
- Height represents Business Units completed in each period
- Shows consistency and productivity trends
- Higher bars = more work completed

**Orange Line - Provisioning Value** (if visible)
- Monetary value of work completed
- Helps correlate productivity with revenue
- Should generally trend upward with BU values

**Dashed Line - Cost** (if visible)
- Cost of the provisioner for each period
- Allows calculation of return on investment
- Helps with resource planning

**Summary Metrics:**
- **Average BU**: Mean performance across all periods
- **Provisioning Value**: Average monetary contribution

**How to Interpret:**

**Consistent Performer:**
- Steady bar heights across periods
- Reliable team member
- Predictable output

**Improving Performer:**
- Increasing bar heights over time
- Learning curve or process improvements
- Positive trend

**Variable Performer:**
- Fluctuating bar heights
- May indicate workload variations or training needs
- Investigate periods of low performance

**Seasonal Patterns:**
- Regular ups and downs
- May reflect business cycles or leave patterns
- Normal for many businesses

**Actions You Can Take:**
- Compare different provisioners to identify best practices
- Identify training opportunities for underperforming team members
- Plan workload distribution based on individual capabilities
- Edit cost information (admin only) using the edit icon

---

## 🔧 Interactive Features

### Date Range Selection
- Use the date pickers to analyze specific time periods
- Default shows current week (or previous week if today is Monday)
- All charts update when dates are changed

### Download Functionality
- Every chart and data point can be downloaded for detailed analysis
- Downloads provide Excel files with complete order details
- Use for further analysis or reporting to management

### Real-time Updates
- Data refreshes automatically when filters change
- Loading indicators show when data is being fetched
- Switch "Show Provisioning Value" toggle (authorized users only)

---

## 💡 Best Practices for Using This Dashboard

### Daily Monitoring
1. Check "Orders in Provisioning Stage" for current workload
2. Review "Abnormal Orders" count - aim for zero
3. Monitor individual provisioner performance

### Weekly Analysis
1. Compare current week performance to previous weeks
2. Identify any provisioners who need support
3. Review group type distribution for capacity planning

### Monthly Review
1. Analyze trends in the performance chart
2. Download detailed data for management reporting
3. Compare month-over-month improvements

### Data Quality Management
1. Address abnormal orders promptly
2. Ensure all orders have complete information
3. Train team members on proper data entry

---

## 🚨 When to Take Action

### Immediate Action Required:
- **High abnormal order count**: Data quality issues need fixing
- **Zero orders for a provisioner**: May indicate workload imbalance
- **Significant performance drops**: Investigate and support team members

### Weekly Attention:
- **Trending increases in workload**: Plan resource allocation
- **Uneven group type distribution**: Balance team skills and training
- **Consistently low performers**: Provide additional training or support

### Monthly Planning:
- **Capacity trends**: Plan hiring or training based on workload patterns
- **Performance variations**: Develop improvement strategies
- **Financial trends**: Align with business planning and budgets

---

## 📞 Getting Help

If you need assistance interpreting the data or have questions about:
- **Missing data**: Contact the admin team
- **Performance questions**: Speak with your team lead
- **Technical issues**: Submit a support ticket
- **Data quality**: Work with the order entry team

Remember: This dashboard is designed to help you understand team performance and workload distribution. Use it to make informed decisions about resource allocation, training needs, and process improvements.