# Housing-Data-Modelling-Metrics-PowerBI






## Project Overview

This project builds on the cleaned dataset created in [Housing-Data-Cleaning-ETLProject]([https://github.com/ваш_логин/Housing-Data-Cleaning-ETL](https://github.com/EkatarinaMail/Housing-Data-Cleaning-ETL) by developing a complete analytical solution in Power BI. The main goal was to design a reliable data model, create business KPIs using DAX, and present the results in an interactive dashboard for a UK housing association.
The dashboard allows users to monitor rent arrears, outstanding repairs, and vulnerable tenant information while providing accurate and consistent reporting for business decision-making.


## Key Skills Demonstrated


* Relationship Management: I resolved granularity issues between property records and tenant information by merging the required data in Power Query before loading it into the model. This prevented many-to-many relationships and kept the model simple and reliable.

![Power Query Table Merging - Granularity Resolution](https://github.com/user-attachments/assets/bc0008e9-8924-41ab-a797-1c0908969b6d)
*Granularity Resolution via Power Query Table Merging*

* Dimensional Modelling: I designed a Star Schema by separating transactional repair data into a central fact table and connecting it to property and calendar dimension tables. This structure improved model performance and made reporting more efficient.

![Star Schema Data Model Architecture](https://github.com/user-attachments/assets/193afce8-2d04-4985-838c-968cb0c2df2f)
*Star Schema Model Architecture*

* Time Intelligence: I created a dedicated calendar table using DAX and connected it to the repairs table with both active and inactive relationships. This made it possible to analyse repairs based on both the logged date and the completed date.

* DAX Calculations: I developed reusable DAX measures to calculate key business metrics, including total rent arrears, outstanding repairs, and the percentage of vulnerable tenants receiving Universal Credit.
Dashboard Design: I created a clean and easy-to-read dashboard using cards, charts, and consistent formatting. I also improved usability by removing unnecessary categories and applying proper chronological sorting to ensure reports were clear for non-technical users.

![Power BI Property Performance Dashboard - Desktop View](https://github.com/user-attachments/assets/a7d7fd54-a715-42d9-b92b-df4445a0e214)
*Property Performance Dashboard*

* Data Validation: Before completing the project, I verified the DAX calculations by connecting Excel directly to the Power BI model and comparing the results with independent Pivot Tables. This confirmed that the dashboard metrics matched the source data accurately.

![Data Validation via Excel Pivot Tables and DAX Verification](https://github.com/user-attachments/assets/4f3974ff-ac16-4df2-bd76-7bc5e3a18c4b)
*Data Validation using Excel Pivot Tables*

## Tools Used 

Power BI Desktop, Power Query, DAX, Microsoft Excel (Pivot Tables), DAX Studio.


