**Project Name: dynamic Sales vs. Budget Performance Monitor**

**1. Business Challenge:**
Stakeholders needed a centralized view to track sales revenue against budget targets (KPIs) and identify which products and customers were driving growth or causing deficits.

**2. Solution & Features:**
I built a multi-page Power BI report transforming raw transactional data into actionable insights:

**3. KPI Tracking & Trend Analysis:**

    a. Created dynamic KPI cards to instantly show the Sales-to-Budget gap (e.g., 1.14M variance).
  
    b. Used Line Charts to visualize the "Actual vs. Budget" trend, highlighting seasonal dips (e.g., the visible drop in August) to prompt immediate investigation.

**4. Product & Customer Segmentation:**

    a.  Developed ranking visuals ("Top 10 Customers" & "Top 10 Products") to help the sales team focus on high-value clients like Jordan Turner.
  
    b.  Utilized Donut Charts to reveal portfolio concentration, showing that the "Bikes" category accounts for over 95% of total sales.

**5. Granular Drill-Down:**
Designed a "Customer Details" view with Matrix visuals, allowing users to drill down from regional performance to specific customer monthly contribution.

**6. Geospatial Analysis:**
Integrated Map visualizations to track sales distribution across North America, Europe, and Asia.

**7. Technical Stack:**

    a. Data Modeling: Built a Star Schema (Fact Sales, Dim Customer, Dim Product, Dim Date) for optimized performance.
  
    b. DAX Measures: Wrote complex measures for Total Sales, Budget Variance, and Time Intelligence calculations.
  
    c. Interactivity: Implemented Slicers (Year, Month, City) and page navigation to enhance user experience.
