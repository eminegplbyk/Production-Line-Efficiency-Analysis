# Production Line Efficiency & Downtime Analysis

This project analyzes production-line efficiency and downtime data using Power BI. The dashboard helps identify the main causes of production interruptions and compare operational performance across products and operators.

Dashboard Preview

[Dashboard Preview](images/Production_Line_Efficiency_Dashboard.png)

Project Objective

The goal is to monitor production performance, identify downtime drivers, and support improvement opportunities through an interactive dashboard.

Tools Used

* Power BI
* Power Query
* DAX
* CSV datasets

Key Metrics

* Total Batches
* Total Downtime
* Average Batch Time
* Average Efficiency

Key Insights

* The dashboard highlights the downtime causes that have the greatest impact on production continuity.
* Operator-level efficiency comparisons make performance differences easier to identify.
* Product filtering enables focused analysis of efficiency and downtime patterns.
* Downtime error-type distribution supports prioritizing operational improvement actions.

Project Structure

```text
Production_Line_Efficiency_Analysis/
│
├── data/
│   ├── downtime-factors.csv
│   ├── line-downtime.csv
│   ├── line-productivity.csv
│   ├── metadata.csv
│   └── products.csv
│
├── images/
│   └── Production_Line_Efficiency_Dashboard.png
│
├── Production_Line_Efficiency_Analysis.pbix
└── README.md
```

How to Use

Download the `.pbix` file and open it with Power BI Desktop. Use the product slicer to explore the dashboard interactively.
