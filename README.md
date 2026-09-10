# 📦 Samsung Supply Chain & Logistics Dashboard

An interactive multi-page **Power BI** report designed to analyze end-to-end supply chain operations, tracking financial performance, vendor lead times, warehouse safety stock, carrier delays, and sales channel profitability.

---

## 🖼️ Dashboard Preview

### 1. Home / Navigation Portal
Landing portal featuring product highlights and navigation controls to jump across operational views.
![Home View](./Supply%20Chain%20%26%20Logistics%20Dashboard_page-0001.jpg)

### 2. Overview Dashboard
High-level summary tracking Gross Revenue ($186.86M), Net Revenue ($176.95M), Profit ($48.56M), Perfect Order Rate (75%), inventory levels, and carrier delays.
![Overview Dashboard](./Supply%20Chain%20%26%20Logistics%20Dashboard_page-0002.jpg)

### 3. Supplier Analytics
Evaluates supplier lead times (11.53 days avg), quality scores, order quantities, total unit costs ($78.13M), and vendor distribution across countries.
![Supplier Dashboard](./Supply%20Chain%20%26%20Logistics%20Dashboard_page-0003.jpg)

### 4. Inventory & Production
Monitors warehouse inventory value (160K), safety stock (89K), defect rates, turnover rate (1.17), and reorder points by product line.
![Inventory Dashboard](./Supply%20Chain%20%26%20Logistics%20Dashboard_page-0004.jpg)

### 5. Shipment & Logistics
Tracks carrier delivery performance, shipment costs ($19.42M), delivered percentage (75.29%), and primary delay causes such as carrier capacity and port congestion.
![Shipment Dashboard](./Supply%20Chain%20%26%20Logistics%20Dashboard_page-0005.jpg)

### 6. Customer & Revenue Analytics
Analyzes revenue vs. profit across sales channels (Online, Retailer, Direct), discount distribution ($9.92M total), and product category performance.
![Customer Dashboard](./Supply%20Chain%20%26%20Logistics%20Dashboard_page-0006.jpg)

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop:** Core platform used to construct data models, design responsive UI layouts, and create navigation features.
* **DAX (Data Analysis Expressions):** Used to build key metrics including Profit Margins (27.44%), Perfect Order Rate (75%), and safety stock reorder thresholds.
* **Power Query:** Utilized for data cleaning, transforming supplier logs, and merging logistics dataset tables.
* **CSV / Excel:** Primary data storage for product SKUs, shipment tracking records, and sales transaction logs.

---

## ⚙️ How I Built This Dashboard

1. **ETL & Data Transformation:**
   * Standardized raw supplier lead times, shipment costs, and sales channel data using Power Query.
2. **Data Modeling & Relationships:**
   * Established a relational data structure linking product SKUs with supplier records, inventory status, and shipment tracking IDs.
3. **DAX Measures & KPIs:**
   * Formulated critical operational metrics:
     * **Financials:** Gross Revenue (`$186.86M`), Net Revenue (`$176.95M`), Profit (`$48.56M`), and Margin (`27.44%`).
     * **Logistics Performance:** Total Shipments (`8K`), Delivered (`75.29%`), Total Delays (`573`), and Average Lead Time (`11.53 days`).
     * **Quality Control:** Defective Units (`24K`), Safety Stock (`89K`), and Average Quality Score (`96.63`).
4. **Interactive UI Layout:**
   * Designed a cohesive theme incorporating custom navigation buttons and product slicers across all six analytical modules.

---

## 📂 Repository Structure

```text
Supply_Chain_Dashboard/
│
├── Supply Chain & Logistics Dashboard_page-0001.jpg # Home view preview
├── Supply Chain & Logistics Dashboard_page-0002.jpg # Overview page preview
├── Supply Chain & Logistics Dashboard_page-0003.jpg # Supplier page preview
├── Supply Chain & Logistics Dashboard_page-0004.jpg # Inventory page preview
├── Supply Chain & Logistics Dashboard_page-0005.jpg # Shipment page preview
├── Supply Chain & Logistics Dashboard_page-0006.jpg # Customer page preview
├── README.md                                        # Documentation file
└── Samsung Supply Chain & Logistics Dashboard/      # Project directory
    ├── Supply Chain & Logistics Dashboard.pbix      # Main Power BI file
    └── [Data Files / CSVs]                          # Source data files
