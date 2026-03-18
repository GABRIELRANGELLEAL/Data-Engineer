# Customer Analytics KPI Pipeline

This project demonstrates a scalable **customer analytics pipeline built with PySpark**.

The objective of the pipeline is to transform raw customer transaction data into business-ready KPI datasets that can be used in analytics dashboards and business intelligence tools.

The project follows common **analytics engineering patterns**, separating the pipeline into logical layers responsible for extraction, feature engineering, and metric aggregation.

---

# Pipeline Architecture

The pipeline follows a layered architecture in which raw data is progressively transformed into analytical datasets consumed by dashboards.

Raw Data  
↓  
Master Dataset  
↓  
Enriched Dataset  
↓  
Metrics Aggregation  
↓  
BI Dashboards
