## **`Amazon Laptop Sales Dashboard (Power BI)`**
🔍 # **Project Overview**

This project analyzes Amazon laptop sales data to extract actionable insights on pricing, configurations, and brand performance. The dataset was cleaned, enriched, and modeled to build an interactive Power BI dashboard.


## **`Data Cleaning & Feature Engineering`**
-Handled missing and inconsistent values across the dataset
-Replaced blank/null entries with "Unknown" to maintain data integrity and avoid aggregation issues
-Standardized brand and categorical fields

-Created new derived columns:**

-CPU Family – grouped processors into meaningful categories (e.g., i3, i5, i7, Ryzen series)
-OS Family – categorized operating systems (Windows, macOS, Chrome OS, etc.)
-OS – refined operating system labels for better analysis
-Ensured correct data types for numerical and categorical fields

## **`Why This Matters`**
-Prevents data loss during aggregation (no dropped nulls)
-Improves grouping and segmentation in visuals
-Enables deeper analysis like CPU vs sales, OS trends, etc.

## **`Dashboard Highlights`**
-Sales distribution by brand
-Price trends across configurations
-RAM vs pricing insights
-Graphics type contribution (Integrated vs Dedicated)
-CPU & OS-based analysis using newly created features

## **`Key Insights`**
-High-performance CPU families (i5/i7, Ryzen) dominate sales
-Windows-based systems lead in volume, while macOS targets premium segments
-Filling missing values with "Unknown" ensures unbiased aggregation