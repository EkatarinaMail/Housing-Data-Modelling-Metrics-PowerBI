# Housing-Data-Modelling-Metrics-PowerBI

![Power BI Housing Compliance and Validation Walkthrough](https://github.com/user-attachments/assets/8342b927-6b42-48e8-a70a-ae99d7d4eaf4)
*Interactive Dashboard with Data Validation*



## Project Overview

This project builds on the dataset prepared in [Housing-Data-Cleaning-ETL project]( https://github.com/EkatarinaMail/Housing-Data-Cleaning-ETL) where the raw data was cleaned and transformed using Power Query. The main goal was to design a reliable data model, create business KPIs using DAX, and present the results in an interactive dashboard for a UK housing association.
The final report provides an easy way to monitor key operational and financial metrics, supporting day-to-day business decisions.


## Key Skills Demonstrated

* Relationship Management: I resolved granularity issues between property records and tenant information by merging the required data in Power Query before loading it into the model. This prevented many-to-many relationships and kept the model simple and reliable.

![Power Query Table Merging - Granularity Resolution](https://github.com/user-attachments/assets/bc0008e9-8924-41ab-a797-1c0908969b6d)
*Granularity Resolution via Power Query Table Merging*

* Dimensional Modelling: Structured the data into a Star Schema by separating transactional repair data into a central fact table and connecting it to property and calendar dimension tables. This structure improved model performance and made reporting more efficient.

![Star Schema Data Model Architecture](https://github.com/user-attachments/assets/193afce8-2d04-4985-838c-968cb0c2df2f)
*Star Schema Model Architecture*

* Time Intelligence: Added a dedicated calendar table using DAX and configured active and inactive relationships. This made it possible to analyse repairs based on both the logged date and the completed date.

* DAX Measures: Developed reusable DAX measures for key business KPIs, including rent arrears, outstanding repairs, and the percentage of tenants receiving Universal Credit.

* Dashboard Design: Designed a clean and easy-to-use dashboard with cards, charts, and consistent formatting. Applied chronological sorting and removed unnecessary categories to improve readability for non-technical users.

![Power BI Property Performance Dashboard - Desktop View](https://github.com/user-attachments/assets/a7d7fd54-a715-42d9-b92b-df4445a0e214)
*Property Performance Dashboard*

* Data Validation: Before completing the project, I verified the DAX calculations by connecting Excel directly to the Power BI model and comparing the results with independent Pivot Tables. This verified that the DAX calculations produced accurate results.

![Data Validation via Excel Pivot Tables and DAX Verification](https://github.com/user-attachments/assets/4f3974ff-ac16-4df2-bd76-7bc5e3a18c4b)
*Data Validation using Excel Pivot Tables*

## Tools Used 

Power BI Desktop, Power Query, DAX, Microsoft Excel (Pivot Tables), DAX Studio.

## Outcome

The project resulted in a complete analytical solution, including a Star Schema data model, reusable DAX measures, and an interactive Power BI dashboard. The calculations were independently validated in Excel to ensure the reported figures matched the source data.
