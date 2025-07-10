## Project Overview
Palmoria Group, a leading Nigerian manufacturing company, is facing scrutiny over gender inequality, pay gaps, and compliance with new salary regulations. As an HR Analytics expert, I was tasked to analyze the company’s HR data, uncover key insights, and provide actionable recommendations to management.

##### Objective: Address gender-related issues, salary structure, pay gap, and bonus allocation across regions and departments.
###### Tools Used: Power BI (data cleaning, main analysis and dashboard), GitHub (documentation).

### Data Cleaning Steps
###### Removed Ex-Employees:

 - Filtered out employees with no salary (as they are no longer with the company).

###### Removed NULL Departments:

 - Excluded all rows with Department marked as “NULL”.

###### Assigned Generic Gender:

 - Labeled employees with missing/blank gender as “Undisclosed”.

###### Standardized Data Types:

 - Converted salary to numeric and ensured consistency in region and department names.

###### Merged Bonus Rules:

 - Joined employee data with bonus rules on Department and Rating to assign correct bonus percentages.

###### Calculated Bonus and Total Pay:

 - Bonus Amount = Salary × Bonus %

 - Total Pay = Salary + Bonus Amount

###### Created Salary Bands:

 - Grouped salaries into $10,000 bands for compliance and distribution analysis.

## Analysis & Visualizations
### Key Business Questions & Methods
###### Question	Method/Visual
   1. What is the gender distribution (overall, by region, by department)?	Donut/Bar/Stacked Bar Chart
   2. What are the rating distributions by gender?	Stacked Bar/Matrix
   3. Is there a gender pay gap? By department/region?	Box Plot/Bar/Matrix
   4. Does Palmoria meet the $90,000 minimum salary regulation?	KPI Card/Bar Chart
   5. What is the pay distribution by $10,000 bands and by region?	Stacked Bar/Column Chart
   6. Calculate and visualize bonus allocation (individual, region, company-wide)	Table/Matrix/KPI/Bar Chart
## Key Insights
 - Gender Distribution: [e.g., 60% Male, 35% Female, 5% Undisclosed overall; breakdown by region/department]

 - Ratings by Gender: [e.g., Female employees in Lagos have higher average ratings]

 - Gender Pay Gap: [e.g., Pay gap exists in Department X and Region Y]

 - Minimum Salary Compliance: [e.g., 97% meet $90,000 minimum; 3% below threshold]

 - Salary Bands: [e.g., Most employees in $90,000–$100,000 band; visualized by region]

 - Bonus Payouts: [e.g., Total company bonus payout: $X; highest in Lagos region]


## Dashboard Preview
()

## Recommendations
Address gender pay gaps in highlighted departments and regions.

Ensure all employees are paid at least $90,000 as per regulation.

Improve gender disclosure rates for better analytics.

Use bonus and rating insights to inform performance management.
