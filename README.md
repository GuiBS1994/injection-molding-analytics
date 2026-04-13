# Injection Molding Analytics

## Overview

This project implements a data analytics pipeline for injection molding machines, integrating real-time IoT machine data with production orders to generate automated performance insights.

The system is designed as a scalable MVP, starting with partial manual data integration and evolving toward full ERP/MRP connectivity.

---

## Business Problem

Injection molding operations generate massive volumes of cycle data, but extracting actionable insights is difficult due to:

* Lack of direct linkage between machine data and production orders
* High data volume (thousands of records per day)
* Low usability of raw reports for decision-making

---

## Solution Approach

This project builds a structured data pipeline with the following layers:

1. **Data Source**

   * MySQL database (machine data via ESP sensors)

2. **Manual Data Bridge (MVP)**

   * SharePoint / Excel for production order control

3. **Data Processing**

   * Power BI (data modeling, filtering, KPI generation)

4. **Automation**

   * Power Automate (daily report distribution)

---

## Key Features

* Cycle time deviation analysis (above/below standard)
* Automated daily reporting
* Configurable data filtering (ignore initial/final cycles)
* Scalable architecture for future ERP integration

---

## Project Structure

* `/docs` → Documentation
* `/data` → Input templates (Excel / SharePoint)
* `/powerbi` → Dashboard files
* `/automate` → Automation flows
* `/sql` → Queries and data extraction logic
* `/roadmap` → Project planning and timeline

---

## Future Improvements

* Direct SQL integration with ERP/MRP system
* Full automation of production order linkage
* Advanced anomaly detection
* Predictive analytics for process optimization

---

## Author

Production Engineering & Data Analytics Project
