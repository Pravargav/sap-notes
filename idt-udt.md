# IDT vs UDT in SAP BusinessObjects

## 🌐 First, what is a **Universe**?

A **universe** is like a **bridge** between your database and your reports (WebI, Crystal, etc.).

- It hides complex tables/SQL.  
- Shows only **business terms** like *Customer, Sales, Profit*.  

To build this universe, you use a **tool** → either **UDT** or **IDT**.

---

## 🔹 UDT (Universe Design Tool)

- The **old tool** for building universes.  
- Creates **.UNV universes**.  
- Can connect to **only one database** at a time.  
- Simpler, but **limited**.  
- Still works, but SAP is phasing it out.  

👉 **Example:** If you build a universe in UDT, you can only connect to an **Oracle DB** OR a **SQL Server DB**, not both together.

---

## 🔹 IDT (Information Design Tool)

- The **new tool** (introduced in BO 4.0).  
- Creates **.UNX universes**.  
- Can connect to **multiple databases** at once (Oracle + HANA + Excel in one universe).  
- More **secure, reusable, and future-proof**.  
- Recommended by SAP.  

👉 **Example:** With IDT, you can build a universe that combines **sales data from Oracle** + **finance data from SAP HANA** into one report.

---

## 🔹 Quick Comparison (Simple Words)

| Feature | **UDT (Old)** | **IDT (New)** |
|-----------------|---------------------------------|-----------------------------------------|
| Universe type | UNV | UNX |
| Sources | 1 database only | Multiple databases |
| Future support | Legacy (phased out) | Recommended (future-proof) |
| Use case | Older BO systems | Modern BO setups |

---
