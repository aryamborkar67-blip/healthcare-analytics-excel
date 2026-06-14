# Healthcare Operations Analytics & AI Validation Suite

An end-to-end data analytics and algorithm validation suite tailored for hospital management and clinical triage auditing. This portfolio project demonstrates core data engineering, logic formatting, cross-sheet data aggregation, and machine learning performance evaluation utilizing Microsoft Excel.

## 📊 Project Components & Features

### 1. Patient Triage & Operational Risk Ledger (`Patient_Data` Sheet)
* **Synthetic Data Generation:** Generated a 20-row clinical dataset modeling real-world patient tracking metrics (Ages, Blood Sugar Levels, Admission/Discharge Dates, Department Splits, and Billing Metrics) utilizing random sampling functions (`RANDBETWEEN`).
* **Automated Clinical Triage:** Engineered conditional logic arrays (`IF` statements) paired with targeted Conditional Formatting rules to dynamically flag "High Risk" diabetic and hypertensive patient profiles across hospital networks.
* **Operational Calculations:** Handled basic date arithmetic to seamlessly calculate precise Patient Length of Stay (LOS) across diverse inpatient environments.

### 2. Executive Healthcare Dashboard (`Executive_Dashboard` Sheet)
* **Cross-Worksheet Aggregation:** Developed structural data pipelines using cross-sheet references to isolate raw processing layers from clean executive summaries. Calculated crucial hospital metrics including Average Patient Stay (`AVERAGE`) and Total Operational Revenue (`SUM`).
* **Financial Data Visualization:** Created interactive 2D Clustered Column charts tracking overall billing distributions across key clinical departments (ICU, General, Pediatrics).
* **High-Density Reporting:** Removed default gridlines to deliver a sleek, application-canvas feel and configured custom page layouts to export clean, single-page executive PDF reports.

### 3. Machine Learning Performance Evaluation Module (`Model_Evaluation` Sheet)
* **Algorithm Performance Auditing:** Structured a diagnostic confusion matrix environment (True Positives, False Positives, False Negatives) modeling an AI tumor detection computer vision algorithm.
* **BODMAS/PEMDAS Formulation:** Constructed highly precise mathematical equations to measure critical AI classification metrics including **Model Precision** and **Model Recall** (`=B2/(B2+B3)`).
* **Logic Auditing:** Utilized formula auditing frameworks to step through deep calculation layers, ensuring algebraic integrity before production export.

## 📁 Included Files
* **[Click Here to View the Executive PDF Report](Healthcare_Operational_Dashboard.pdf):** A clean, production-ready snapshot of the operational dashboard exported for senior stakeholders.
* **`PROJECT-1_EXE.DASHBOARD.xlsx`:** The fully functional, interactive raw workbook containing all automated formulas, formatting rules, and cross-sheet pipelines.
