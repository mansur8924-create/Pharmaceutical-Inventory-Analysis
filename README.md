# Pharmaceutical-Inventory-Analysis
Project Overview

This project focuses on optimizing pharmaceutical compounding operations by analyzing the intersection of prescription fulfillment, ingredient inventory, and physician referral patterns. By architecting a Star Schema data model, I transformed disparate compounding logs into an interactive intelligence dashboard that tracks fulfillment accuracy, ingredient turnover, and high-value provider relationships.

Tools & Technologies

Power BI: Primary tool for multi-source data integration and dashboard orchestration.

DAX (Data Analysis Expressions): Utilized for complex time-intelligence calculations and inventory turnover metrics.

Star Schema Modeling: Established a robust relationship between the central Fact_CompoundingLog and descriptive dimensions (Dim_Doctors, Dim_Ingredients).

Data Transformation: Normalizing unit measurements and handling multi-source CSV ingestion.

Project Structure

Fact Table (Fact_CompoundingLog): The central ledger containing quantitative transactional data, including dates, quantities, and fulfillment status.

Dimension Tables:

Dim_Doctors: Metadata regarding referring physicians and practice locations.

Dim_Ingredients: Detailed catalog of chemical compounds, stock levels, and procurement costs.

Analytics Report: The final .pbix dashboard showcasing operational KPIs.

Key Insights & Metrics

Fulfillment Efficiency: Analyzing the cycle time from compounding request to patient delivery.

Inventory Velocity: Identifying "Fast-Moving" vs. "Stagnant" pharmaceutical compounds to reduce waste.

Referral Analytics: Mapping physician specialties to specific compounding needs for strategic resource allocation.
