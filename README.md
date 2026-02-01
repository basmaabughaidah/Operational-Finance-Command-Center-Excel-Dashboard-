# Operational Finance Command Center (Excel Dashboard)

**Precision-first** Excel dashboard that unifies **Purchase Orders (POs)**, **invoicing**, and **milestone-based payments** into a single operational finance view at the project level.

> This repository intentionally includes **documentation and screenshots only**.  
> The operational workbook and raw datasets are **not published** to protect privacy, client confidentiality, and commercially sensitive information.

---

## What this command center covers

### 1) Purchase Orders (Projects)
- PO value breakdown by **project, client, destination, and category** (e.g., A/B)
- **Multi-currency handling** with EGP-standardized reporting
- Dimensions/quantity summaries and scope indicators
- **Spatial KPIs**: total area (m²), average area, and the largest project by area

### 2) Invoicing Control (Invoice Monitor)
- Invoice register aligned to projects / clients / categories
- **Tax controls**: VAT and withholding (WHT) tracking
- **Schedule accuracy**: expected vs. actual invoicing dates for monitoring delays and cashflow risk

### 3) Payment Milestones (Payment_Conditions)
- Milestone-based payment plans (percentage/value per milestone)
- Expected vs. actual invoicing dates per milestone
- Invoice reference, milestone notes, and execution tracking

---

## Decision-ready insights this dashboard supports
- **Financial clarity:** totals, averages, currency mix, and EGP-standardized reporting
- **Operational accuracy:** value vs. area comparisons and scope-based prioritization
- **Client impact:** concentration of projects by top clients and dependency signals
- **Market visibility:** distribution by destination/country to highlight active markets and expansion opportunities

---

## Currency conversion note (important)
EGP equivalents depend on Excel-based FX logic (e.g., dynamic exchange-rate retrieval).  
If FX retrieval is unavailable or fails, conversion cells may **fall back to non-converted values**.  
For the most accurate snapshot, refresh calculations and data connections inside Excel (e.g., **Data → Refresh All**).


## Data privacy (must-read before publishing screenshots)
Screenshots must not include:
- Client names (unless explicitly approved for public disclosure)
- PO references, invoice numbers, internal IDs
- Phone numbers, emails, or any personal identifiers
- Exact commercial amounts if confidential

---

## Tech stack
- **Microsoft Excel:** dashboard visuals, pivots, formulas, KPI layout
- **Power Query:** data cleaning, shaping, merges, refreshable transformation pipeline

---

## Disclaimer
This repository documents the reporting approach and UI patterns only.  
It does not provide the operational workbook or underlying datasets.


## Screenshots
## Screenshots

![Screenshot 01](Screenshot%2001.png)
![Screenshot 02](Screenshot%2002.png)
![Screenshot 03](Screenshot%2003.png)
![Screenshot 04](Screenshot%2004.png)
![Screenshot 05](Screenshot%2005.png)
![Screenshot 06](Screenshot%2006.png)
![Screenshot 07](Screenshot%2007.png)

