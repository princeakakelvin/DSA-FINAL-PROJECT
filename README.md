## Project Overview
Palmoria Group, a leading Nigerian manufacturing company, is facing scrutiny over gender inequality, pay gaps, and compliance with new salary regulations. As an HR Analytics expert, I was tasked to analyze the company’s HR data, uncover key insights, and provide actionable recommendations to management.

##### Objective: Address gender-related issues, salary structure, pay gap, and bonus allocation across regions and departments.
###### Tools Used: Power BI (data cleaning, main analysis and dashboard), GitHub (documentation).

## Data
#### Main Analysis [https://github.com/princeakakelvin/Palmorial-HR-Group-Analysis/blob/main/Aka_Kelvin_%20Palmoria_Gruop_HR-Analysis.pbix]

##### Raw Data [https://github.com/princeakakelvin/Palmorial-HR-Group-Analysis/blob/main/Palmoria%20Group%20Bonus%20Rules.csv]
               [https://github.com/princeakakelvin/Palmorial-HR-Group-Analysis/blob/main/Palmoria%20Group%20emp-data%20csv.csv]
               
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

###### Calculated Bonus and Total Pay: Using DAX

 - Bonus Amount = Salary × Bonus % [<img width="1013" height="724" alt="Bonus Amount" src="https://github.com/user-attachments/assets/1c1fffd2-43ea-458c-8e83-b2ca456d1c06" />
]

 - Total Pay = Salary + Bonus Amount [<img width="1012" height="703" alt="total salary" src="https://github.com/user-attachments/assets/be5d0e0c-4efc-4d73-ac5a-8e21e87918e0" />
]

###### Created Salary Bands:

 - Grouped salaries into $10,000 bands for compliance and distribution analysis. [<img width="1124" height="693" alt="salary band" src="https://github.com/user-attachments/assets/0555b98e-f94a-4e98-aad3-a1dbdd4ecdab" />
]

## Analysis & Visualizations
### Key Business Questions & Methods
###### Question	Method/Visual
   1. What is the gender distribution (overall, by region, by department)?	
   2. What are the rating distributions by gender?	
   3. Is there a gender pay gap? By department/region?
   4. Does Palmoria meet the $90,000 minimum salary regulation?
   5. What is the pay distribution by $10,000 bands and by region?
   6. Calculate and visualize bonus allocation
## Key Insights
 - Gender Distribution: [<img width="726" height="385" alt="Screenshot 2025-07-15 001349" src="https://github.com/user-attachments/assets/69c45a4a-f532-4874-81d1-1c29e0500218" />
]

 - Ratings by Gender: [<img width="740" height="423" alt="Screenshot 2025-07-15 000514" src="https://github.com/user-attachments/assets/d8491500-b451-4a07-9df3-784c4714f856" />
]

 - Gender Pay Gap: [<img width="504" height="301" alt="Screenshot 2025-07-15 000801" src="https://github.com/user-attachments/assets/64252867-e2cb-4c6b-9892-3967fd2f97da" />
]

 - Minimum Salary Compliance: [More than 50% of the employees did not meet the 90,000 threshold]

 - Salary Bands: [Most employees in $90,000–$100,000 band; <img width="756" height="436" alt="Screenshot 2025-07-15 001717" src="https://github.com/user-attachments/assets/e3dc846f-0db9-4a69-932a-f4ab8c401bc7" />
]

 - Bonus Payouts: [Total company bonus payout highest in Kaduna region <img width="782" height="448" alt="Screenshot 2025-07-15 002458" src="https://github.com/user-attachments/assets/2b2b1a44-4c2c-4ca2-a0a1-a3bd3034881a" />
]


## Dashboard Preview
(<img width="775" height="441" alt="palmoria dashboard" src="https://github.com/user-attachments/assets/c4cd1554-38c4-458c-8733-6294e7a8fecf" />
)

## Recommendations
Address gender pay gaps in highlighted departments and regions.

Ensure all employees are paid at least $90,000 as per regulation.

Improve gender disclosure rates for better analytics.

Use bonus and rating insights to inform performance management.
