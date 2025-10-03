# 📊 Import Jobs vs Upload Jobs vs Export Jobs in SAP Analytics Cloud (SAC)  

| Feature | Import Jobs | Upload Jobs | Export Jobs |
|----------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------|
| **Purpose** | Bring data from **remote sources** (e.g., SAP BW, HANA, S/4HANA, SQL DB). | Bring data from **flat files** (CSV, XLSX) manually uploaded by user. | Send data **out of SAC** to external systems or flat files. |
| **Data Source**| Live or remote connections (cloud/on-premise systems). | Local files uploaded from desktop. | Target system (SAP system, database, or flat file). |
| **Automation** | Can be scheduled to run automatically. | Can also be scheduled but usually manual upload. | Can be scheduled to regularly push data out. |
| **Use Case** | Pulling actuals/transactions from ERP, BW, databases. | Uploading planning templates or small datasets manually. | Pushing planning results or reports back to ERP/BW or exporting as file. |
| **Example** | Import monthly *Sales data* from SAP S/4HANA. | Upload *Excel-based budget file* into planning model. | Export *final approved budget* from SAC back to S/4HANA or to a CSV file. |

---

## 🧠 Easy Analogy  

- **Import Job = Pull 📥** → System-to-SAC automatic data load.  
- **Upload Job = Drop 📂** → User manually uploads files into SAC.  
- **Export Job = Push 📤** → SAC sends data out to another system/file.
