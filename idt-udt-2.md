# 🧩 IDT vs UDT – Detailed Explanation

| **Feature** | **IDT (Information Design Tool)** | **UDT (Universe Design Tool)** |
|--------------|-----------------------------------|--------------------------------|
| **Purpose** | New-generation tool for designing `.unx` universes | Legacy tool used for `.unv` universes |
| **Semantic Layer Design** | Uses two-layer architecture:<br>- **Data Foundation** – defines tables, joins, and connections <br>- **Business Layer** – defines business objects like measures and dimensions | Uses single-layer structure:<br>- **Classes and Objects** directly represent database columns |
| **Version Control** | Integrated with repository projects, supports versioning and teamwork | No built-in version control — versions handled manually |
| **Deployment** | Publishes universes directly to the BO Repository from IDT | Publishes via BO Designer |
| **Performance** | Optimized for modern databases like SAP HANA and multi-source systems | Less optimized; works best with traditional relational databases |
| **Usage Recommendation** | Use for new universe development or migrating old universes | Use for maintaining legacy universes already built in older systems |

---

### 📝 Summary
- **IDT** → Modern tool for creating `.unx` universes (recommended for new projects).  
- **UDT** → Legacy tool for `.unv` universes (maintained for older systems).  
- **IDT** supports better performance, version control, and modern database connections like **SAP HANA**.
