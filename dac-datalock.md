
PRAVARGAV JETTY <pravargav24@gmail.com>
10:14 AM (0 minutes ago)
to Pravargav

# 🔑 Difference between Data Access Control (DAC) and Data Locking in SAP SAC  

| Feature            | Data Access Control (DAC)                                                                 | Data Locking                                                                 |
|--------------------|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Purpose**        | Controls **who can see or edit** specific dimension members (access restriction).         | Controls **when and which data can be changed** during planning cycles.      |
| **Level**          | Works at the **dimension level** (e.g., Region, Product, Cost Center).                    | Works at the **data intersection level** (e.g., Entity + Version + Period).  |
| **Focus**          | **User-based security** → decides visibility & edit rights per user/team.                 | **Process-based security** → decides if data is still editable or frozen.    |
| **Read/Write**     | Yes → separate **Read** and **Write** permissions in the dimension.                       | No read/write separation → either data is **locked (blocked)** or **open**. |
| **Typical Use**    | Restricting users to only their region/entity. <br> Example: India manager sees only India | Freezing planning data after submission. <br> Example: Q1 numbers locked.    |
| **Configuration**  | Enable DAC in a **dimension** → add Read/Write columns → assign users.                     | Create **Data Locking Task** → define drivers (Version, Period, Entity).     |
| **Scenario**       | Security & confidentiality.                                                               | Workflow & data governance.                                                  |
