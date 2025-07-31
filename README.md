
# 📊 Northwind Business Insights – Power BI Dashboard

This project presents an interactive dashboard built with Power BI, based on the classic Northwind dataset. It demonstrates key skills in data modeling, DAX, data storytelling, and user experience (UX) design applied to a realistic business performance analysis.

---

## 📸 Dashboard Preview

![Northwind Dashboard Cover](./assets/Coverpage.png)

---

## 📁 Data Model

This star-schema data model includes:

- **Fact Table:**
  - `Orders` – sales-related data including dates, customers, employees, and geographic references

- **Dimension Tables:**
  - `Customers` – customer details and country
  - `Employees` – staff involved in the sales process
  - `Products` – product catalog and category data
  - `Territory` and `Region` – geographical sales areas
  - `Calendar` – a custom date table created using the DAX `CALENDAR` function, enabling robust time-based analysis

All tables are connected through one-to-many relationships using keys such as `CustomerID`, `EmployeeID`, `RegionID`, and `Date`.

---

## 📈 Key Metrics and KPIs

The dashboard includes:

- Gross and net revenue by year, month, and category  
- Year-over-Year (YoY) revenue growth  
- Top 5 and Bottom 5 products, customers, and employees  
- Sales performance by region, country, and product category  
- Interactive maps by territory

---

## 🎨 UI/UX Design

- Custom cover page for presentation
- Tabbed navigation across sections (Overview, Employee, Customer, Product)
- Clean and professional color palette using a custom JSON theme
- Informative tooltips, navigation buttons, and visual hierarchy

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query** for data transformation
- **DAX** to create custom metrics such as:
  - `Gross Revenue`
  - `Net Revenue`
  - `YoY Growth`
  - `Calendar` table

---

## 📌 Requirements

- Power BI Desktop (latest version recommended)  
- Included `Northwind.xlsx` dataset for reference and reproducibility

---

## 📂 Repository Structure

```
📁 Northwind-PowerBI/
│
├── 📄 README.md
├── 📊 NorthWind_Report_Cassia.pbix
├── 📈 Northwind.xlsx
├── 🎨 tema-northwind-business-clarity.json
└── 🖼️ assets/
    ├── Coverpage.png
    └── background_northwind.jpg
```

---

## 🚀 Project Value

This dashboard can be used for:

- BI and data analytics portfolios  
- Commercial sales performance simulations  
- Training and learning best practices in Power BI, DAX, and dashboard UX

---

## 👩 Author

**Cássia Magalhães**  
[LinkedIn](https://www.linkedin.com/in/cassiamagalhaes) • [Email](mailto:cassiacarvalho.pe@gmail.com)

---

## 📄 License

This project is released under the MIT License. See `LICENSE` for more information.
