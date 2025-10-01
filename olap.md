# OLAP Sources in SAP BusinessObjects

## 🌐 First, what is OLAP?

- **OLAP** = Online Analytical Processing.  
- It’s about analyzing **multi-dimensional data** (like Sales by Region, Product, Year).  
- OLAP sources are systems/databases that store data in a way that supports **hierarchies, drill-downs, and cubes**.

---

## 🔹 OLAP Sources in BO

SAP BO can connect to many OLAP systems. Common OLAP sources are:

1. **SAP BW (Business Warehouse)**
   - Most common OLAP source for BO.
   - Uses **InfoCubes, BEx Queries, and CompositeProviders**.
   - Supports hierarchies, variables, and prompts.

2. **SAP HANA (Multidimensional Models)**
   - BO tools (like WebI, Lumira, AfO) connect to HANA views.
   - Supports multidimensional analysis with hierarchies.

3. **Microsoft Analysis Services (MSAS / SSAS)**
   - OLAP cubes from Microsoft SQL Server Analysis Services.

4. **Oracle Essbase**
   - A multidimensional OLAP server from Oracle.

5. **Other OLAP engines**
   - IBM Cognos TM1, Teradata OLAP, etc. (depending on connectors).

---

## 🔹 Why are OLAP Sources Important?

- They provide **multi-dimensional data** (dimensions + measures).  
- Allow features like:
  - Drill-down / Roll-up (Year → Quarter → Month → Day).  
  - Slice and Dice (Region = "Asia").  
  - Pivot-style analysis.  

---

## 🔹 BO Tools that Use OLAP Sources

- **Web Intelligence (WebI)** → Connects via OLAP universes or direct BEx queries.  
- **SAP Analysis for Office (AfO)** → Directly connects to BW and HANA OLAP structures.  
- **Crystal Reports for Enterprise** → Can use OLAP sources.  
- **SAP Lumira** → Connects to OLAP for visual exploration.  

---
