# ☕ Starbucks Beverage Analysis — Power BI Dashboard
An interactive Power BI dashboard analyzing Starbucks' global beverage menu — covering caffeine content, calories, sugar levels, and category-wise distribution across 33 beverages.

## 📊 Project Overview & Core Architecture\
<img width="1325" height="741" alt="Screenshot 2026-08-11 165821" src="https://github.com/user-attachments/assets/ddffb255-db64-49b6-b42b-c405a7c340fe" />

This analytical project delivers a 360-degree view of Starbucks beverages by transforming raw nutritional data into clear, actionable business metrics. The dashboard layout is intentionally structured around four core KPI tiles that track Total Beverages, Average Sugar, Average Calories, and Average Caffeine across the entire product mix. To uncover deep nutritional trends, the report incorporates a strategic calorie trend line that instantly highlights which specific beverage categories are the most calorie-dense, helping users identify high-energy items at a glance.

The menu taxonomy is further broken down through a clean donut chart that visualises the global presence and percentage share of each beverage family, including Classic Espresso, Frappuccinos, Shaken Iced Beverages, and traditional Brewed Coffee. Alongside this, multi-directional horizontal bar charts compare average caffeine levels across specific drinks like White Chocolate Mocha, Tazo Green Tea, Java Chip, Hot Chocolate, and Caffè Mocha. To ensure the most critical data points capture immediate attention, a specialized custom card layout highlights the Top 5 Highest Caffeine Beverages, creating a dedicated spotlight section for the menu's most high-octane choices.

## 🎛️ Interactive Elements & UX Design
User experience and deep exploratory analysis are at the heart of this dashboard's design. The report features a responsive Protein Range slider spanning 0 to 20 grams, which allows users to dynamically filter down the entire beverage menu based on precise macronutrient goals. To accommodate diverse consumer choices, a granular Beverage Preparation dropdown and checklist slicer are integrated directly into the canvas, enabling instant drill-downs by milk types, espresso additions, or custom blending styles. 

Every single visual asset on the canvas is connected through full bi-directional cross-filtering. This means selecting a specific category or drink choice instantly filters and recalculates the rest of the dashboard, allowing users to perform root-cause analysis and discover complex relationships between preparation styles and total nutritional impact.

## 🛠️ Data Engineering & Development Techniques
Building this dashboard required rigorous data preparation and custom modeling using Power BI Desktop. During the initial Power Query Extract, Transform, Load (ETL) phase, multiple data cleanliness issues were resolved, such as transforming the caffeine column from a Text format into a clean Numeric data type to allow for proper mathematical aggregation. Furthermore, geographic mapping errors caused by inconsistent ISO alpha-2 country codes were systematically cleaned and standardized to ensure the visual representations render perfectly without data loss.

Advanced DAX (Data Analysis Expressions) calculated measures were written to handle dynamic averaging for calories, sugar, and caffeine across ever-changing filter contexts. To bridge the gap between technical data and corporate branding, a custom JSON dashboard theme was built from scratch using official Starbucks corporate brand guidelines, featuring the recognizable Starbucks green palette (#00704A and #1E3932) to deliver a polished, executive-ready presentation.

## 📌 Critical Business Insights Discovered
The data model reveals several compelling baselines regarding the Starbucks global beverage portfolio. Across all 33 analyzed beverages, the baseline average caffeine concentration sits at exactly 81 mg, while the average energy density stands at 194.30 kcal per drink, heavily driven by syrup-dense customization options. The single most significant outlier in the entire dataset is the Classic Espresso category, which dramatically outpaces every other beverage family on the menu by commanding a peak average caffeine content of 293.75 mg. Ultimately, the data proves that the core menu footprint is overwhelmingly dominated by the Coffee and Frappuccino blended categories, which represent the main volume drivers for the global business.

---
**👨‍💻 Author:** Mohan Kumar | Data Science Student & Analytics Explorer
🔗 [Connect with me on LinkedIn](https://linkedin.com) | [Explore my repositories on GitHub](https://github.com)
