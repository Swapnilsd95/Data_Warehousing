# Data_Warehousing
This repository includes the project of Data Warehouse

Objective:
• To develop data warehouse comprising of various healthcare related datasets taken from cms.org
• To create a Data Model for healthcare datasets used using ER Studio.
• To deliver insights of number of services, Medicare payment amounts, number of beneficiaries, the number of APC services, hospitals' average total estimated submitted charges.
• Insights about the payment services used and charges in healthcare domain over United States.
• Discover relatability between suppliers, providers and medical equipment, prosthetics, orthotics, and supplies.
• Visualize the relationships on various analytical tools such as Tableau and SSAS.

Data Source:
1. The Physician and Other Supplier Public Use File
Link: https://data.cms.gov/Medicare-Physician-Supplier/Medicare-National-HCPCS-Aggregate-Summary-Table-CY/2zuc-y5mm/data
2. The Outpatient Hospital Utilization and Payment Public Use File
Link: https://data.cms.gov/Medicare-Outpatient/State-Summary-of-Outpatient-Hospital-Charge-Data-b/iwge-h6r6
3. The Inpatient Utilization and Payment Public Use File
Link: https://data.cms.gov/Medicare-Inpatient/Inpatient-Prospective-Payment-System-IPPS-Provider/tcsp-6e99
4. Durable Medical Equipment, Prosthetics, Orthotics and Supplies (DMEPOS) National Aggregate table
Link: https://data.cms.gov/Medicare-Durable-Medical-Equipment-DME-/Medicare-Referring-DMEPOS-HCPCS-National-Aggregate/gduq-te83

Steps included while building Data Warehousing:
1. Data Preprocessing
2. Creating Staging Table, Achieve Table and Destination table 
3. Creating Dimension Models, Entity Relation Diagram
4. Making use of Lookup tables, derived Column, slowly changing Dimension in SSIS according to the desired results
5. Creating the Multidimensional OLAP Cube was creates using SQL Server Analysis Services (SSAS) in MS Visual Studio (SSDT)
6. Data Visualization using Tableau
