# 🏗️ Chicago Building Violations Analysis

🔍 Project Overview

This project analyzes 784,225 building violation records in Chicago’s 15th Ward, focusing on regulatory compliance, fines, case dispositions, and seasonal trends. The dataset includes violation codes, fine amounts, hearing dates, and geographic data, providing a comprehensive view of enforcement patterns.

🚀 Key Objectives

Data Cleaning & Transformation: Handle missing values, convert date formats, and create new variables for analysis.
Exploratory Data Analysis (EDA): Identify violation trends, assess fines, and explore case dispositions.
Visualization: Use ggplot2 to analyze seasonal trends, fine distributions, and violation frequencies.
Geospatial Analysis: Map violations in the 15th Ward using leaflet.
📊 Data Processing & Analysis

Dataset: 784,225 observations, 22 variables.
Key Variables: Violation Description, Violation Code, Imposed Fines, Case Disposition, Violation & Hearing Dates.
Data Cleaning:
Identified 544 missing values, ensuring 97.23% completeness.
Converted date variables (POSIXct) & calculated CityDelay (days between violation & hearing).
Added seasonal categories (Winter, Spring, Summer, Fall).
Exploratory Insights:
452 unique violations and 456 unique violation codes identified.
Most common case disposition: "Liable."
Highest fines: "Default" cases.
Peak violation season: Summer (construction activity increases).
Weak positive correlation (0.2242) between fines and administrative costs.
📍 Geospatial & Historical Context

Mapped violations in the 15th Ward using leaflet.
15th Ward covers Brighton Park, Gage Park, and West Englewood.
Historical Fact: Chicago’s first major manufacturing industry was established here in 1857.
🛠️ Tools & Techniques

Programming: R
Libraries Used: tidyverse, ggplot2, lubridate, leaflet, naniar
Techniques: Data cleaning, correlation analysis, seasonal trend analysis, geospatial mapping
🔑 Key Insights

✅ Liable cases are most common, but Default cases incur the highest fines.
✅ Violations peak in Summer, possibly due to increased construction activity.
✅ Many offenders default on fines, preferring to pay without contesting.
✅ Declining fine amounts in 2024 suggest an increase in continuance cases.

📌 Conclusion

This project demonstrates the power of data mining and visualization in understanding urban regulatory compliance. The insights can help policymakers refine enforcement strategies, fine structures, and case resolution processes for better city governance.

