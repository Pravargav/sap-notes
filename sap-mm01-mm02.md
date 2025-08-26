Excellent 👌 You’re now asking at the **transaction level** — let’s place **MM01 / MM02** properly in the SAP structure.

  

## **1. What are MM01 and MM02?**

 

 

- **MM01** → Transaction code to **create a material master**.

 

- **MM02** → Transaction code to **change a material master**.

 

- (MM03 is for display).

 



 

A **material master** is the core record for anything a company buys, makes, stores, or sells (raw materials, finished products, services, etc.).

  

## **2. Where do they exist in SAP?**

 

🔹 **Layer → Application Layer**

 

 

- **Module → MM (Materials Management)**

 

- **Sub-process → Master Data Management**

 



 

So:

 

 

- **MM01/MM02** exist in the **Logistics → Materials Management → Material Master** area of SAP GUI Easy Access.

 



 

👉 Example navigation in Easy Access:

 `SAP Easy Access    → Logistics        → Materials Management            → Material Master                → Material                    → Create (Special) → MM01                    → Change           → MM02                    → Display          → MM03 `  

## **3. How does it connect with technical tools?**

 

When you run **MM01 / MM02**:

 

 

1. You enter data like material type, unit of measure, purchasing info, valuation class, etc.

 

2. That data gets stored in **HANA database tables** (e.g., MARA, MARC, MBEW, MVKE, etc.).

 

3. Other modules use it: 

 

  - **PP** → uses materials for production.

 

  - **SD** → uses materials for sales orders.

 

  - **FI/CO** → uses valuation class for accounting.

 

  - **WM/EWM** → stores stock at bin/location level.

 



 

 

4. **SAC or BW** can later analyze material data (e.g., stock aging, sales per material).

 



  

## **4. Analogy**

 

Think of **MM01/MM02** as the “Add/Edit Product” screens in an e-commerce admin panel.

 

 

- The product you create (material master) will later be used in orders, stock management, and financials.

 



  

✅ So final placement:

 

 

- **MM01/MM02 = T-codes inside SAP GUI (Easy Access) → Application Layer → MM Module → Material Master Data

