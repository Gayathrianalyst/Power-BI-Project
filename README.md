# Power-BI-Project
**Project Title:** Bank Loan Performance Analysis with Power BI
### **Objective:**
   This project analyzes a lending loan dataset to uncover relationships between borrower behavior (e.g., income, debt-to-income ratio) and loan characteristics (e.g., amount, term). By examining loan statuses (fully paid, charged off, late), it provides actionable insights to help financial institutions optimize lending strategies, mitigate credit risk, and improve portfolio performance.

### **Tools Used:**
   - Power BI for data visualization and interactive dashboards.
   - Data cleaning and transformation with Power Query.


### 1. **Importing Data**
   - **Objective**: Import necessary datasets into Power BI for analysis.
   - **Execution**: Simple and straightforward. Importing the sheets "LoanDetails" and "BorrowerDetails" from an Excel file ensures that all relevant data is ready for analysis.

### 2. **Transformation Using Power Query**
   - **Data Cleaning**:  
     The steps listed (e.g., handling missing values, duplicates, and inconsistencies) are great for ensuring the data is reliable and consistent. This is critical before any further analysis.
   - **Data Transformation**:  
     - Column transformations, renaming, and creating new calculated columns will allow us to tailor the dataset to analysis.
     - **Delinquency status** is a great feature to help segment the data further, and transforming the columns to appropriate formats will ease the analysis process.

### 3. **Data Modeling**
   - **Relationships**:  
     Setting relationships between tables (with cross-filtering) ensures that you can leverage all data across the tables for integrated analysis.

### 4. **Creating Measures and Calculated Columns Using DAX**
   - The DAX formulas for remaining installments, borrower verification counts, and loan status percentages will allow you to create actionable metrics that are central to understanding loan performance and borrower behavior.

### 5. **Creating Comprehensive Reports**
   - **Report 1: Loan Performance Analysis**:  
     This report will give stakeholders a clear understanding of how loans are performing across various attributes. Key visuals like the "Loan Status Distribution" pie chart and "Fully Paid Loan Percentage" gauge chart help quickly communicate key insights. 
   - **Report 2: Borrower Profile Analysis**:  
     This report dives deeper into the characteristics of the borrowers. Using visuals like KPI, bar charts, and donut charts gives detailed insights into aspects like income, verification status, delinquency, and loan purpose. These help in segmenting and analyzing borrower behavior in a more granular way.

### Key Considerations:
- **Dynamic Exploration**: Including slicers and filters (e.g., Issue Date, Loan Purpose, Delinquency Status) allows users to interact with the reports and explore the data based on specific needs, which is great for actionable insights.
- **Tooltips**: Adding tooltips ensures that users can hover over data points to get additional context, which improves the usability and experience of the reports.
- **Summary Sections**: Including a summary or insights section at the end of each report is helpful for key takeaways, especially for stakeholders who need quick insights rather than detailed analysis.

### Conclusion:
The steps i've listed are well-structured and appropriate for a comprehensive loan and borrower analysis in Power BI. This approach combines essential data transformation, powerful DAX measures, and insightful visualizations, which will help stakeholders make data-driven decisions regarding loan performance and borrower profiles.
