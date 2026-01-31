# 📅 Annual Leave Tracker (Excel)

## 📌 Situation

Human Resource teams often manage annual leave using manual spreadsheets that are prone to errors, overlaps, and policy violations. Common challenges include:

- Inaccurate leave day calculations  
- Leave overlaps between employees  
- Difficulty enforcing department-level leave policies  
- No automated validation or warnings  
- High risk of accidental formula edits  

These challenges increase administrative workload and expose organizations to operational risks.

---

## 🎯 Objective

The objective of this project is to build a **robust, policy-compliant Annual Leave Tracker** using **Excel**, capable of:

- Accurately calculating annual leave entitlement  
- Enforcing organizational leave rules automatically  
- Detecting and explaining leave overlaps  
- Reducing manual HR effort  
- Providing a protected, user-friendly system suitable for daily HR operations  

---

## ⚙️ Implementation

### 1️⃣ Core Data Structure
- Designed a structured Excel table to capture:
  - Employee Name  
  - Department  
  - Employment Start Date  
  - Leave Start Date  
- Separated **manual input columns** from **formula-driven columns**.

---

### 2️⃣ Automated Leave Calculations
- Calculated **Years of Service** using completed years only  
- Implemented leave entitlement logic:
  - 16 days for the first completed year  
  - +1 day for every 2 additional completed years  
  - Leave entitlement capped at **30 days** as per policy  
- Automatically computed **Leave End Date** excluding:
  - Sundays  
  - Public holidays  

---

### 3️⃣ Policy-Based Leave Overlap Logic
Advanced overlap validation was implemented using Excel formulas:

- **Same Department Rule**
  - Employees in the same department cannot be on leave during overlapping periods  

- **Different Department Rule**
  - Leave periods must be at least **7 days apart**  

The system automatically:
- Detects conflicts  
- Flags violations  
- Identifies *which employee(s)* the leave overlaps with  

Clear warnings are displayed only when violations exist; otherwise, the field remains blank.

---

### 4️⃣ Visual & Usability Enhancements
- Conditional formatting to highlight:
  - Overlapping leave warnings  
  - Valid leave schedules  
- Clean column layout for HR readability  
- Formula columns locked to prevent accidental edits  
- Manual entry columns remain editable  

---

### 5️⃣ Protection & Governance
- Sheet protection implemented to:
  - Secure calculation logic  
  - Prevent formula tampering  
- Optional password protection  
- Hidden formulas for a cleaner HR-facing experience  

---

## ✅ Conclusion

This Annual Leave Tracker demonstrates how **Excel**, when properly structured, can deliver a **policy-driven, automated HR solution** without requiring external systems.

The tracker:
- Eliminates manual leave calculation errors  
- Enforces organizational leave policies automatically  
- Reduces HR administrative workload  
- Improves transparency and compliance  
- Is ready for real-world operational use  

This project is ideal for organizations seeking a **lightweight, cost-effective HR leave management tool** built on widely available software.

---

## 🔧 Future Enhancements
- Multi-year leave balance tracking  
- Departmental leave calendars  
- Management dashboards  
- Power Query integration with HR systems  

---

## 🛠 Built With
- Microsoft Excel 

---

## 👤 Author
**Omusilwa Victor**  
Solve Consultancy
