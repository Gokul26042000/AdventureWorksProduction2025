> AdventureWorksProduction2025
AdventureWorks2025 Production Analytics: End-to-end data project analyzing enterprise manufacturing workflows, inventory optimization, and supply chain efficiency.

>>> Project Overview
This project delivers an enterprise-grade Power BI reporting solution designed for senior management to monitor and optimize global *inventory health, manufacturing performance, and production efficiency*. Using the comprehensive **AdventureWorks2025** database, the end-to-end implementation transforms over 50 raw tables into a streamlined, high-performance business intelligence tool focused on inventory optimization and manufacturing variance tracking.

<img width="1322" height="732" alt="image" src="https://github.com/user-attachments/assets/d42ea6c1-016a-4494-acd1-4d71791ccf1c" />


>>> Core Metrics & KPIs Implemented
The report centers on four critical, high-level operational metrics engineered via DAX:

- **Total Inventory Value:** Tracks capital tied up in warehouse stock
- **Manufacturing Scrap Rate %:** Monitors material waste and manufacturing defects by measuring total scrapped quantities against total produced volume.
- **On-Time Work Orders %:** Evaluates production timeline reliability by calculating the percentage of manufacturing work orders completed on or before their scheduled due date.
- **Stock-out Risk Count:** A proactive risk mitigation metric tracking the exact number of product SKUs where current inventory falls below established safety stock thresholds.

---

>>> Specialized Data Views & Visualizations
The final dashboard translates these KPIs into targeted analytical views tailored for leadership decision-making:

1. Inventory Optimization View
- **Stock-to-Safety Stock Ratio:** Advanced visual analysis comparing actual inventory levels against safety stock thresholds across product subcategories to immediately expose overstocking or imminent stockout risks.
- **Subcategory Inventory Value**: A tabular breakdown mapping total stocked quantities and their corresponding financial value across specific product subcategories.

> 2. Manufacturing Efficiency View
- **Work Order Lead Time & Cost Trends:** Dynamic line charting tracking production cycle times alongside financial performance by visualizing the variance between actual cost and planned cost over time.

> 3. Executive Slicers (Global Filters)
To facilitate rapid deep-dives, the report includes intuitive, hierarchical filtering across:
- **Timeline:** Production Year, Quarter, and Month.
- **Product Hierarchy:** Product Category and Subcategory.

---

>>> *Technical Workflow & Architecture*

1. Extraction & Transformation (ETL)
- **Targeted Schema Reduction:** Analyzed the 50+ table database dump to isolate data relevant to production, inventory, and product dimensions.
- **Power Query Engineering:** Standardized raw tables within Power Query Editor (PQE), creating custom conditional columns, cleaning null values, and ensuring data integrity.

2. Data Modeling
- **Star Schema Design:** Architected a robust Star Schema by establishing direct relationships between transactional Fact tables and descriptive Dimension tables.
- **DAX Architecture:** Developed scalable measures for all target KPIs, ensuring performance optimization across large rows of production data.

3. UI/UX Design & Deployment
- **Prototyping:** Wireframed low-fidelity layouts to ensure clean alignment and high scannability.
- **Executive Delivery:** Deployed a highly interactive, clean UI that balances high-level executive summaries with granular, drill-down analytics.
