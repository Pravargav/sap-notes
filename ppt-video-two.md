# Cognizant’s SAP Analytics – Typical Solution Architecture

This diagram shows Cognizant’s SAP Analytics – Typical Solution Architecture in four main layers, moving from data sources at the bottom to business-facing analytics tools at the top.
Here’s the breakdown layer by layer:


---

### 1. Source Layer (Bottom)

Where raw data originates. Two categories:

SAP Sources

SAP S/4HANA – Core ERP system (transactional data).

SAP Concur – Travel & expense data.

SAP Ariba – Procurement data.

SAP SuccessFactors – HR & talent management data.

SAP ERP, SAP NetWeaver, SAP BW – Legacy ERP and data warehousing.

SAP Integrated Business Planning (IBP) – Supply chain planning.


Non-SAP Sources

SCADA – Industrial automation data.

External Data – CSVs, APIs, market feeds.

IoT Data – Connected devices/sensors.




---

### 2. Data Integration Layer

Where raw data from SAP and non-SAP systems is connected, cleaned, and prepared for analysis.

SAP Data Intelligence – Orchestrates, cleans, and integrates data from multiple sources.

SAP Cloud Platform Integration Suite (implied through governed data flow) – Ensures secure, governed data movement.

This layer connects to both SAP Data Warehouse Cloud and SAP BW/4HANA.



---

### 3. Database / Data Warehouse Layer

Where data is stored and modeled for analytics.

SAP BW/4HANA – Enterprise data warehouse for structured analytics.

SAP Data Warehouse Cloud – Cloud-based, flexible data storage and modeling.

SAP HANA – In-memory database for real-time processing.

S/4HANA Embedded Analytics – Real-time operational analytics directly on the transactional database.



---

### 4. Data Consumption Layer (Top)

Where business users and analysts access insights.

SAP Fiori / Fiori Tiles – Custom, role-based dashboards and apps.

SAP Analytics Cloud (SAC) –

BI Reporting – Dashboards and visualizations.

Planning – Financial and operational planning.

Predictive / AI / ML – Machine learning and forecasting.


SAP BusinessObjects – Traditional reporting and enterprise BI.

SAP BPC – Business Planning and Consolidation.

SAP Analytics Hub – Centralized access to analytics assets.



---

#### How Data Flows

1. Data sources (SAP & non-SAP) produce raw transactional, operational, or sensor data.


2. Data Integration Layer harmonizes and governs data (via SAP Data Intelligence, ETL).


3. Warehouse Layer stores and models this data for fast queries (BW/4HANA, HANA, DWC).


4. Consumption Layer tools like SAC, BusinessObjects, and Fiori allow users to visualize, plan, and predict outcomes.




---

#### Key Points

Governed Data ensures compliance, quality, and consistency across the pipeline.

Hybrid model – Supports both cloud (SAC, DWC) and on-premise (BW/4HANA, BusinessObjects).

End-to-end coverage – From IoT/SCADA data ingestion to AI-powered analytics and enterprise planning.



---

