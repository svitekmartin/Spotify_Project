
### 1. Overview of the Dataset

This dataset tracks Spotify’s financial and user engagement metrics from 2017 onward. It offers a detailed snapshot of revenue streams, costs, and user segmentation across premium and ad-supported tiers. It’s a valuable resource for analyzing business performance, user trends, and profitability across different service models.

The dataset includes following key metrics:

-   **Date**: Reporting period.
    
-   **Total Revenue**: Combined earnings from subscriptions and ads.
    
-   **Cost of Revenue**: Direct costs to deliver services (e.g., infrastructure, royalties).
    
-   **Gross Profit**: Revenue minus cost of revenue.
    
-   **Premium Revenue**: Income from paying subscribers.
    
-   **Premium Cost Revenue**: Costs specific to premium services.
    
-   **Premium Gross Profit**: Profit from premium subscriptions.
    
-   **Ad Revenue**: Revenue from ad-supported users.
    
-   **Ad Cost of Revenue**: Delivery costs for ad-supported services.
    
-   **Ad Gross Profit**: Profit from ad-supported tier.
    
-   **MAUs**: Total monthly active users.
    
-   **Premium MAUs**: Active paying users.
    
-   **Ad MAUs**: Active users on the free tier.
    
-   **Premium ARPU**: Average revenue per premium user.
    
-   **Sales and Marketing Cost**: Customer acquisition and brand spend.
    
-   **R&D Cost**: Investment in new features and technologies.
    
-   **G&A Cost**: Overhead and operational expenses.
    

### 2. Key Stakeholders and Their Interests

-   **Sarah – Head of Strategy**  
    Focus: Long-term growth and user trends.  
    Needs: Insights into growth patterns across both premium and ad-supported users to inform strategic planning.
    
-   **Mark – Director of Revenue**  
    Focus: Revenue optimization.  
    Needs: Detailed breakdown of revenue by stream (premium vs. ad), and Premium ARPU trends to assess monetization effectiveness.
    
-   **Olivia – VP of Operations**  
    Focus: Operational efficiency and cost management.  
    Needs: Full view of cost structure—revenue delivery, marketing, R&D, and G&A—to uncover savings opportunities without hurting performance.




## 3. Design Plan

### Understanding which staekholder needs which data

**Sarah, Head of Strategy :**
She is focused on long-term growth and strategic direction.
Sarah wants to see insights into user growth trends, particularly for premium
and ad-supported users, to shape future strategies.

**Growth & Revenue Objectives:**
✅ Identify revenue growth drivers – Determine whether Premium or Ad-Supported users contribute more to revenue growth.
✅ Understand user trends – Track Monthly Active Users (MAUs) across Premium and Ad-Supported segments.
✅ Optimize ARPU (Average Revenue Per User) – Analyze how Premium ARPU changes over time.
✅ Highlight cost-saving opportunities – Assess Cost of Revenue trends for Premium and Ad-Supported models.

**Efficiency & Profitability Objectives:**
✅ Evaluate profitability – Monitor Gross Profit and Gross Margin % for Premium and Ad-supported revenue.
✅ Assess cost allocation – Examine the impact of Sales & Marketing, R&D, and G&A Costs on profitability.
✅ Identify cost-efficiency improvements – Look at trends in Cost of Revenue vs. Revenue Growth.

**User Growth Metrics:**
📌 **Total MAU Growth Rate** = (Current MAUs – Previous MAUs) / Previous MAUs * 100
📌 **Premium MAU Growth Rate** = (Current Premium MAUs – Previous Premium MAUs) / Previous Premium MAUs * 100
📌 **Ad MAU Growth Rate** = (Current Ad MAUs – Previous Ad MAUs) / Previous Ad MAUs * 100

**Revenue Metrics:**
📌 **Total Revenue Growth Rate** = (Current Revenue – Previous Revenue) / Previous Revenue * 100
📌 **Premium Revenue Growth Rate** = (Current Premium Revenue – Previous Premium Revenue) / Previous Premium Revenue * 100
📌 **Ad Revenue Growth Rate** = (Current Ad Revenue – Previous Ad Revenue) / Previous Ad Revenue * 100

**Profitability Metrics:**
📌 Gross Profit Margin = (Gross Profit / Total Revenue) * 100
📌 Premium Gross Profit Margin = (Premium Gross Profit / Premium Revenue) * 100
📌 Ad Gross Profit Margin = (Ad Gross Profit / Ad Revenue) * 100

**Efficiency & Cost Metrics:**
📌 **Cost of Revenue %** = (Cost of Revenue / Total Revenue) * 100
📌 **Sales & Marketing % of Revenue** = (Sales and Marketing Cost / Total Revenue) * 100
📌 **R&D % of Revenue** = (R&D Cost / Total Revenue) * 100
📌 **General & Admin % of Revenue** = (General and Admin Cost / Total Revenue) * 100

**User Monetization Metrics:**
📌 **Premium ARPU** (Avg. Revenue Per User) = Premium Revenue / Premium MAUs
📌 **Ad Revenue Per Ad MAU** = Ad Revenue / Ad MAUs

*Additional Data for Sarah:*
✅ Churn Rate (%) – How many users (both premium and ad-supported) are leaving over time.
✅ Retention Rate (%) – How many users stay subscribed after a certain period.
✅ User Engagement (Hours per User per Month) – How actively users engage with Spotify.
✅ Conversion Funnel Analysis – How free users convert to premium users over time.
✅ User Acquisition Cost (UAC) – Cost to acquire a new user (via marketing spend).
✅ Revenue per User Segment – Breaking down revenue by region, device type, or demographics.
✅ Top-Performing Playlists & Genres – Understanding what keeps users engaged.
✅ Competitor Benchmarking – Comparing Spotify's user growth to competitors like Apple Music.

*📊 Potential Visuals for Sarah:*
✅Churn & Retention Trends (Line Chart)
✅Premium vs. Ad-Supported User Growth (Stacked Bar Chart)
✅User Engagement Heatmap (by Region or Age Group)
✅Conversion Funnel (Free → Premium)


**Mark, Director of Revenue :**
Mark is responsible for optimizing revenue streams. He needs a detailed breakdown of how different revenue streams (premium and ad-based) have evolved since 2017, as well as an analysis of Premium ARPU (average revenue per user) to measure profitability per subscriber

**1️⃣ Goals & Objectives (Revenue Focus)**

✅ Track revenue evolution since 2017 – Analyze trends in Total, Premium,and Ad Revenue.
✅ Break down revenue streams – Compare the growth rates of Premium vs. Ad-based revenue.
✅ Measure user monetization – Evaluate Premium ARPU over time.
✅ Identify revenue efficiency trends – Assess Cost of Revenue and its impacton profitability.

**2️⃣ Key Performance Indicators (KPIs)**
To optimize revenue, Mark needs detailed revenue analytics:
**Revenue Growth Metrics:**

**📌 Total Revenue Growth Rate** = (Current Revenue – Previous Revenue) / Previous Revenue * 100
📌 **Premium Revenue Growth Rate** = (Current Premium Revenue – Previous Premium Revenue) / Previous Premium Revenue * 100
📌 **Ad Revenue Growth Rate** = (Current Ad Revenue – Previous Ad Revenue) / Previous Ad Revenue * 100

**Revenue Efficiency Metrics:**

📌 **Cost of Revenue %** = (Cost of Revenue / Total Revenue) * 100
📌 **Premium Cost of Revenue %** = (Premium Cost Revenue / Premium Revenue) * 100
📌 **Ad Cost of Revenue %** = (Ad Cost of Revenue / Ad Revenue) * 100

**User Monetization Metrics:**

📌 **Premium ARPU** (Average Revenue Per User) = Premium Revenue / Premium MAUs
📌 **Ad Revenue Per Ad MAU** = Ad Revenue / Ad MAUs

**Profitability Metrics:**

📌 **Gross Profit** = Total Revenue - Cost of Revenue
📌 **Gross Profit Margin** = (Gross Profit / Total Revenue) * 100
📌 **Premium Gross Profit Margin** = (Premium Gross Profit / Premium Revenue) * 100
📌 **Ad Gross Profit Margin** = (Ad Gross Profit / Ad Revenue) * 100

**3️⃣ Dashboard & Visualizations for Mark**

To help Mark track revenue performance, we can build a Tableau dashboard with:

📊 **Revenue Trends (2017-Present)** – Line charts showing Total, Premium, and Ad Revenue Growth.
📊 **Premium vs. Ad-Based Revenue Breakdown** – Stacked bar charts or area charts.
📊 **Premium ARPU Over Time** – Line graph to track profitability per subscriber.
📊 **Revenue Efficiency (Cost of Revenue%)** – Visualizing how much revenue is spent on costs.
📊 **Gross Profit Trends** – Profitability analysis over time.

**Additional Data for Mark:**

✅ Ad Impressions & Click-Through Rate (CTR) – How well ads are performing.
✅ Premium Plan Breakdown – Revenue from different premium plans (Individual, Family, Student).
✅ Lifetime Value (LTV) per User – Expected revenue per user over their entire subscription.
✅ Cost per Acquisition (CPA) per Revenue Stream – How much is spent acquiring different user types.
✅ Subscription Cancellation Reasons – Understanding why users cancel.
✅ Regional Revenue Trends – How revenue varies across countries.
✅ Platform Revenue Distribution – Revenue share by device (mobile, desktop, smart speakers, etc.).

 **📊 Potential Visuals for Mark:**

Revenue Trends (Premium vs. Ads) (Line Chart)
ARPU Breakdown by Region & Plan Type (Heatmap)
Cost Efficiency Analysis (Revenue vs. Marketing Spend)
Ad Revenue vs. Impressions & CTR (Bubble Chart)

**Olivia, VP of Operations :**

Olivia is focused on operational efficiency. She wants a clear understanding of Spotify’s cost structure, including the cost of revenue, sales and marketing expenses, and research and development costs. Her goal is to identify areas for potential cost reduction without compromising service quality.

**1️⃣ Goals & Objectives (Cost Efficiency Focus)**

✅ Analyze Spotify’s total cost structure – Breakdown of Cost of Revenue, Sales & Marketing, R&D, and General & Administrative (G&A) expenses.
✅ Identify cost trends over time – Understanding how different costs fluctuate and impact profitability.
✅ Find cost-saving opportunities – Determine which areas could be optimized without affecting service quality.
✅ Assess cost-efficiency ratios – Compare revenue against expenses to measure operational effectiveness.

**2️⃣ Key Performance Indicators (KPIs)**

To track operational efficiency, Olivia needs the following cost-related KPIs:

**Cost Breakdown Metrics:**

📌 **Cost of Revenue %** = (Cost of Revenue / Total Revenue) * 100
📌 **Sales & Marketing Cost %** = (Sales & Marketing Cost / Total Revenue) * 100
📌 **R&D Cost %** = (Research & Development Cost / Total Revenue) * 100
📌 **General & Admin Cost %** = (G&A Cost / Total Revenue) * 100

**Efficiency & Profitability Metrics:**

📌 Operating Profit = Total Revenue - (Cost of Revenue + Sales & Marketing + R&D + G&A)
📌 Operating Margin = (Operating Profit / Total Revenue) * 100
📌 Cost-to-Revenue Ratio = Total Costs / Total Revenue
📌 Revenue per Employee (if employee data is available) = Total Revenue / Number of Employees

**Cost Trend Analysis:**

📌 Year-over-Year (YoY) Cost Growth = (Current Year Cost - Previous Year Cost) / Previous Year Cost * 100
📌 Month-over-Month (MoM) Cost Change – For short-term efficiency tracking.

**3️⃣ Dashboard & Visualizations for Olivia**

To provide Olivia with actionable insights, we can build a Tableau dashboard with:

📊 Cost Structure Breakdown – Stacked bar chart showing Cost of Revenue, Sales & Marketing, R&D, and G&A as a % of Total Revenue.
📊 Cost Trends Over Time – Line charts to track cost fluctuations per category.
📊 Cost-to-Revenue Ratio – Visualizing how efficiently revenue is generated.
📊 Profitability Trends – Operating profit and margin analysis over time.
📊 Cost Comparison (YoY & MoM) – Highlighting where cost increases are happening.

**Additional Data for Olivia:**

✅ Operational Costs per User Segment – Cost structure differences for premium vs. ad-supported users.
✅ Server & Infrastructure Costs – How much is spent on hosting and streaming services.
✅ Marketing Spend Efficiency – ROI of marketing campaigns vs. user growth.
✅ Employee Productivity Metrics – Revenue per employee, operational cost per employee.
✅ Customer Support Costs – Support ticket volume, resolution times, and costs.
✅ Licensing Costs per Stream – How much is paid to artists per stream.
✅ Operational Costs by Region – Which markets have the highest cost-to- revenue ratios.

**📊 Potential Visuals for Olivia:**

Cost Breakdown by Category (Pie Chart)
Cost Efficiency Ratio (Line Chart, Trend Over Time)
Marketing Spend vs. Revenue Growth (Scatter Plot)
Server & Infrastructure Cost Trends (Stacked Bar
