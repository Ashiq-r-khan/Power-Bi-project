#  Hospitality Dashboard — Power BI

An interactive business intelligence dashboard built in **Power BI Desktop**, analyzing hotel performance metrics across multiple cities and properties in India.

---

##  Dashboard Preview

>  See `Hospitality_Dashboard.pdf` in this repository for the full dashboard export.

---

##  Key Metrics Analyzed

| Metric | Value |
|--------|-------|
| Total Revenue | **$1.69 Billion** |
| Average Occupancy Rate | **57.8%** |
| Average Daily Rate (ADR) | **12.7K** |
| RevPAR | **7.3K** |
| Realisation % | **70.1%** |
| Average Guest Rating | **3.62 / 5** |

---

##  Cities Covered

- Mumbai — ₹0.66bn revenue
- Bangalore — ₹0.42bn revenue
- Hyderabad — ₹0.32bn revenue
- Delhi — ₹0.29bn revenue

---

##  Dashboard Pages

| Page | Description |
|------|-------------|
| **Home** | Overview & navigation |
| **Dashboard** | Main KPI summary with filters |
| **Key Metrics** | Detailed performance breakdown |
| **TT Revenue** | Revenue trend by week |
| **TT RevPer** | RevPAR trend analysis |
| **TT ADR** | Average Daily Rate trends |
| **TT DSRN** | Daily Sellable Room Nights |
| **TT Occupancy%** | Occupancy rate trends |
| **TT Realisation%** | Realisation % trends |

---

##  Features & Techniques

- **KPI Cards** — Revenue, Occupancy%, RevPAR, ADR, DSRN, Realisation%
- **Interactive Filters** — City, Category, Class, Status, Platform, Month
- **Bar & Line Charts** — Revenue and occupancy by city and time
- **Pie/Donut Charts** — Booking by day type and revenue by category
- **Data Table** — Property-level key metrics breakdown
- **Trend Analysis** — Week-on-week change tracking (May–July 2022)
- **DAX Measures** — Custom calculated metrics and KPIs
- **Data Modeling** — Star schema with fact and dimension tables

---

##  Data Model

```
fact_bookings
fact_aggregated_bookings
dim_hotels
dim_rooms
dim_date
key_Masures_Table
```

---

##  Tools Used

- **Power BI Desktop** — Report design & DAX
- **Power Query** — Data transformation & cleaning
- **DAX** — Custom measures and calculated columns

---

##  Files in This Repository

| File | Description |
|------|-------------|
| `Hospitality_Dashboard.pdf` | Exported dashboard (all pages) |
| `README.md` | Project documentation |

---

##  Author

**Md. Ashiqur Rahman Khan Ashik**
B.Sc. Statistics — Mawlana Bhashani Science and Technology University (MBSTU)
Tangail, Bangladesh



