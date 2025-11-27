# Economic & Payroll Analysis in Czech Republic (2006-2018)

1. **Project overview**
    This Power BI report provides a comprehensive analysis of the economic relationship between industry-specific payroll trends, consumer price inflation (groceries), and macroeconomic indicators (GDP) for the Czech Republic over the period 2006 to 2018. The primary goal is to assess changes in consumer purchasing power and affordability across various sectors.

2. **Key metrics & analysis**
    The report is structured across four pages, using SQL-processed data and key calculated metrics:
    |Metric|Source|Purpose|
    |Average payroll|Measure (DAX)|Dynamic average payroll for the current selection.|
    |Payroll CAGR|Measure (DAX)/Gauge|Benchmark for overall industry annual growth rate.|
    |Product price year-on-year change|Calculated Column (DAX)|Measures annualized inflation for specific product groups.|
    |Purchasing power|Calculated column|The percentage difference between payroll change and price change.|
    |Cumulative GDP growth|Measure (DAX/PRODUCTX)|Tracks the true compound growth of the economy over time.|
    |Cumulative purchasing power growth|Meaure(DAX/PRODUCTX)|Calculates the overall compounded change in consumer affordability over time.|


3. **Report Structure & Navigation**
    The report uses navigation buttons for easy navigation. Use the arrows/button links to navigate the flow:
    |Page|Focus|
    |P1: Payroll summary|High-level payroll trends and overall benchmarks.|
    |P2: Industry payroll details|Industry-specific payroll change comparison.|
    |P3: Price & Affordability|Relationship between wages, prices, and consumer welfare.|
    |P4: Purchasing power & GDP|GDP correlation with consumer purchasing power.|

4. **Data Model and Integrity**
    Source: Raw data is imported from SQL (pre-processed tables like primary_table, task_1_table, task_4_table, etc.).
    Relationships: The data model relies on a central relationship between the SQL tables and the Year dimension table.

5. **Getting Started**
    Open the .pbix file in Power BI Desktop.
    Use Sliders to filter the data by year or industry. Follow the navigation buttons to discover more information.