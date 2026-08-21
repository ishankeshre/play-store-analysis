# Play Store Analysis

## Project Overview

This project analyzes **Google Play Store application data using Microsoft Power BI** to evaluate app performance across categories, ratings, reviews, installations, pricing, and content ratings.

The analysis covers **10,840 valid app records** after removing an invalid category record from the original 10,841-row dataset. The project uses Power Query for data preparation and Power BI for interactive analysis and visualization.

## Objectives

* Analyze the distribution of applications across categories
* Evaluate application ratings and review patterns
* Analyze installation performance
* Compare free and paid applications
* Identify high-performing app categories
* Analyze the relationship between reviews and installations
* Examine application pricing
* Build an interactive Power BI report for business analysis

## Tools & Skills

* Microsoft Power BI
* Power Query
* DAX
* Data Cleaning & Transformation
* Data Modeling
* KPI Analysis
* Data Visualization
* Interactive Dashboard Development
* Business Analysis

## Dataset

The original dataset contains **10,841 records** and **13 attributes**.

After removing an invalid record, the analysis uses **10,840 valid records** representing **9,659 unique applications**.

Key fields include:

* App Name
* Category
* Rating
* Reviews
* Size
* Installs
* Type
* Price
* Content Rating
* Genres
* Last Updated
* Current Version
* Android Version

## Data Preparation

The dataset was prepared using **Power Query** before analysis.

Key preparation steps included:

* Handling missing ratings
* Removing an invalid category record
* Cleaning installation values such as `10,000+` and `1,000,000+`
* Converting reviews and installs into numeric values
* Converting price values into numeric format
* Standardizing data types
* Preparing fields for Power BI analysis

## Analysis Performed

### Category Analysis

* Application count by category
* Average rating by category
* Installation performance by category
* Review volume by category

### Rating Analysis

* Overall average application rating
* Rating distribution
* Category-wise rating comparison
* Comparison of ratings between free and paid applications

### Installation Analysis

* Installation volume across applications
* Category-wise installation performance
* Identification of highly installed applications
* Relationship between reviews and installations

### Pricing Analysis

* Free vs. paid application analysis
* Paid application pricing
* Average paid application price
* Price distribution across applications

### Review Analysis

* Review volume across applications
* Category-wise review analysis
* Relationship between reviews and installations
* Identification of highly reviewed applications

## Power BI Report

The Power BI report contains multiple analytical pages:

* **Basic**
* **Medium 1**
* **Medium 2**
* **Advance**

The report includes KPI cards, slicers, bar charts, column charts, donut charts, line charts, and tables for interactive analysis.

## Key Metrics

* **Original Records:** 10,841
* **Valid Records:** 10,840
* **Unique Applications:** 9,659
* **Total Categories:** 33
* **Free Applications:** 10,039
* **Paid Applications:** 800
* **Average Rating:** 4.19
* **Total Listed Installs:** Approximately 167.63 billion
* **Average Paid App Price:** $13.92
* **Maximum App Price:** $400

## Key Insights

* **Family** is the largest app category with **1,972 applications**, followed by **Game with 1,144** and **Tools with 843**.
* **Events** has the highest average rating at approximately **4.44**, followed by **Education at 4.39** and **Art & Design at 4.36**.
* **Game** has the highest total installation volume at approximately **35.09 billion installs**, followed by **Communication at 32.65 billion** and **Productivity at 14.18 billion**.
* **Game** also has the highest total review volume at approximately **1.59 billion reviews**.
* Approximately **92.6%** of valid applications are free, while approximately **7.4%** are paid.
* Paid applications have a slightly higher average rating of approximately **4.27**, compared with **4.19** for free applications.
* Reviews and installations show a moderate positive correlation of approximately **0.64**, indicating that applications with more reviews generally tend to have higher installation volumes.
* The median installation level is **100,000**, while several major applications have reached the **1 billion+ installation** range.
* The most common content rating is **Everyone**, with **8,714 applications**, followed by **Teen with 1,208 applications**.
* The average price of paid applications is approximately **$13.92**, although the majority of paid apps are priced considerably lower than the maximum observed price of **$400**.

## Business Insights

The analysis indicates that application success is concentrated in a relatively small number of categories. **Game and Communication** applications account for particularly high installation and review volumes, suggesting strong user engagement in these segments.

The analysis also shows that **reviews and installations are positively associated**, making review volume a useful indicator of application reach and user engagement, although it should not be interpreted as a direct cause of higher installations.

## Limitations

* The dataset represents a historical snapshot of Google Play Store applications rather than current market data.
* Installation figures are provided as ranges rather than exact values.
* Some applications contain missing ratings or other incomplete fields.
* Duplicate application records are present in the original dataset.
* Correlation indicates association and does not establish causation.
* The analysis describes historical application performance and should not be treated as current Google Play Store market performance.

## Project Structure

```text
Play-Store-Analysis/
│
├── README.md
├── Play_Store_Analysis.pbix
├── googleplaystore.csv
└── screenshots/
    └── dashboard.png
```

## Conclusion

This project demonstrates the use of **Power BI, Power Query, and DAX** to transform raw Google Play Store data into an interactive analytical report.

The analysis provides insights into application categories, ratings, installations, reviews, pricing, and content ratings while demonstrating practical skills in data cleaning, transformation, KPI development, visualization, and business analysis.

## Author

**Ishan Keshre**

Business Analyst | Data Analytics | SQL | Power BI | Excel
