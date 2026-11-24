# Indian Vehicle Registration & EV Adoption Dashboard

An interactive **Power BI dashboard** that shows how vehicles are registered across India and how fast **Electric Vehicles (EVs)** are being adopted.

---

## 1. Problem Statement

India registers lakhs of new vehicles every year, but it is not easy to see:

- Which **states** register the most vehicles?
- Which **vehicle categories** and **fuel types** are most popular?
- What share of all vehicles are **electric**, and is it growing?
- Which **manufacturers** lead the market?

This dashboard answers these questions in one place, using simple charts and filters.

---

## 2. Dataset

| Item | Details |
|------|---------|
| Records | **500,000** vehicle registrations |
| Fields | **15** columns (state, vehicle category, fuel type, manufacturer, registration year, etc.) |
| Period | **2020 – 2025** |
| Data preparation | Cleaned and prepared with **Python (Pandas)**, then loaded into Power BI |

---

## 3. Tools Used

- **Python (Pandas)** – data cleaning and preparation
- **Power BI Desktop** – dashboard building
- **Power Query** – data loading and shaping
- **DAX** – calculated measures

---

## 4. Key Measures (KPIs)

| KPI | What it means |
|-----|---------------|
| **Total Registrations** | Total number of vehicles registered |
| **EV Registrations** | Number of electric vehicles registered |
| **EV Adoption %** | `EV Registrations ÷ Total Registrations × 100` – out of every 100 vehicles, how many are electric |
| **Manufacturer Count** | Number of different vehicle manufacturers |

> **How EVs are identified:** a vehicle is counted as an EV when its fuel type contains labels such as "Electric" or "Pure EV".

---

## 5. Dashboard Pages

The report has **3 pages, 4 KPI cards and 8 charts**.

### Page 1 – EV Overview
- 4 KPI cards (Total Registrations, EV Registrations, EV Adoption %, Manufacturer Count)
- Registrations by **state**
- **Top states by EV Adoption %**
- EV registrations by **year** (trend, 2020–2025)
- Registrations by **fuel type**
- Registrations by **vehicle category**

### Page 2 – Final Analysis
- Registrations by **vehicle type** (EV vs Non-EV share)
- **Top manufacturers** by registrations (treemap)
- EV registrations by **vehicle category**

### Page 3 – Conclusion
- Summary of the main findings and recommendations

---

## 6. Key Insights

> Fill these in from your dashboard so recruiters see real results.

- Total registrations analysed: **500,000** (2020–2025)
- Overall EV Adoption %: **__ %**
- State with the highest EV Adoption %: **______**
- Most popular fuel type: **______**
- Top manufacturer: **______**
- EV registrations grew from **____** in 2020 to **____** in 2025

---

## 7. Screenshots

<img width="1920" height="1008" alt="Screenshot 2026-11-24 193934" src="https://github.com/user-attachments/assets/99024e43-ec69-4711-ac2f-1b3a084d8642" />
<img width="1920" height="1008" alt="Screenshot 2026-11-24 194002" src="https://github.com/user-attachments/assets/adf85ff4-1efc-4269-9e2f-3507c9d940f8" />

## 8. How to Open This Project

1. Download or clone this repository.
2. Install **Power BI Desktop** (free, Windows).
3. Open `Indian_vehicle_Registration_EV_adoption_Project.pbix`.
4. Use the slicers and click on charts to filter the data.

---

## 9. Repository Structure

```
├── Indian_vehicle_Registration_EV_adoption_Project.pbix
├── screenshots/
│   ├── ev_overview.png
│   ├── final_analysis.png
│   └── conclusion.png
└── README.md
```

---

## 10. What I Learned

- Cleaning large data (500,000 rows) with Python and Pandas
- Writing DAX measures such as EV Adoption %
- Choosing the right chart for each question (bar, line, donut, treemap)
- Turning raw data into insights for decision-making

---

## Author

**Manohar Babu Balaga**
Aspiring Data Analyst | Python • SQL • Power BI • Excel
 balagamanoharbabu123@gmail.com
