# 📊 Uber & Logistics Performance Analysis Dashboard

An enterprise-grade Power BI business intelligence solution designed to analyze ride-hailing and fleet logistics data. This project transforms raw transactional data into actionable operational insights—monitoring revenue performance, optimizing fleet utilization, and evaluating trip efficiency.

---

## 🎯 Business Value & Key Insights
* **Financial Oversight:** Real-time tracking of top-line revenue, fare distributions, and profitability windows.
* **Fleet Optimization:** Comparative analysis across vehicle segments (`SUV`, `Sedan`, `Standard`) to balance asset utilization against customer demand.
* **Operational Efficiency:** Granular monitoring of trip metrics, isolating bottlenecks in trip durations (`clock`) and mileage (`distance`).
* **App-Like User Experience:** Seamless UI/UX design featuring an interactive, dynamic navigation menu for intuitive executive reporting.

---

## 🛠️ Tech Stack & Architecture
* **Power BI Desktop / Project (PBIP):** Built using the modern project structure optimized for Git version control.
* **DAX (Data Analysis Expressions):** Engineered for robust KPI metrics, dynamic aggregations, and performance profiling.
* **Power Query (M):** Utilized for strict ETL processing, data cleansing, and structural schema enforcement.
* **Data Model Architecture:** Optimized relational schema designed for fast query performance and clear cross-filtering.

---

## 📂 Repository Structure
This project leverages the modern Power BI Project (`.pbip`) format, allowing for clean, file-based tracking of report metadata and layouts:

```text
├── [Content_Types].xml       # Core configuration mapping for the Power BI project
├── DataModel                  # Relational schema, tables, and relationship definitions
├── Settings & Metadata       # Report environmental configurations
├── SecurityBindings          # Access control and security parameters
└── Report/
    ├── Layout                # Visual canvas layouts and page-by-page configurations
    ├── SharedResources/
    │   └── BaseThemes/
    │       └── CY24SU10.json # Custom corporate JSON theme for unified color theory and UI consistency
    └── StaticResources/
        └── RegisteredResources/  # High-fidelity UI assets and custom iconography
            ├── Uber_Logo.png     # Brand styling asset
            ├── Home.png          # Navigation element for the landing page
            ├── sales & money.png # Metric indicators for financial tracking
            ├── distance & clock.png # Performance markers for trip logistics
            └── car, suv, sedan.png  # Analytical identifiers for fleet categorization
```

# 🚀 Key Features
Dynamic Navigation Menu: Integrated with slick UI icons (Home, Info, Refresh) ensuring a web-app-like user experience.

Advanced Financial Analytics: Real-time visibility into revenue streams, payment methods, and profitability analysis.

Fleet Demographics: Purpose-built views comparing the demand, utilization, and margins of various vehicle types (SUV, Sedan, Car).

Time & Distance Profiling: Interactive components (including tailored donut-charts) focusing on trip durations (clock) and mileage (distance).

Branded Custom UI: Built utilizing a tailored JSON design schema (CY24SU10.json) to deliver a modern, cohesive, dark/light theme alignment.

# 🛠️ Tech Stack & Tools
Power BI Desktop / Project: Environment utilized for structuring the database relationships and reporting canvas.

DAX (Data Analysis Expressions): Deployed for constructing complex measures, KPIs, and time-intelligence parameters.

Power Query (M Language): Utilized for robust ETL (Extract, Transform, Load) processing to clean and shape raw transaction entries.

JSON: Applied for building the global report aesthetics, typography, and theme styling.

# 📥 How to Use
Clone this repository to your local environment.

Ensure you have the latest version of Power BI Desktop installed.

Open the project folder structure or report file directly within Power BI.

Update the Data Source Settings to point to your respective backend database to refresh and stream data.
