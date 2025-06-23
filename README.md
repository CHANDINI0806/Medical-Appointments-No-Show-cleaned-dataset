# Medical-Appointments-No-Show-cleaned-dataset

#Medical Appointments No-Show – Data Cleaning Project

This project involves cleaning the **"Medical Appointment No-Show"** dataset using **Microsoft Excel** and **Power Query**. The dataset contains over 100,000 medical appointment records from Brazil and tracks whether patients showed up or not.

---

## 📂 Dataset Source

- **Original Dataset**: [Kaggle – No Show Appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **License**: Open for academic and research use.

---

## 🛠 Tools Used

- Microsoft Excel
- Excel Power Query
- Basic Excel formulas

---

##  Data Cleaning Summary

### 🔧 Column Renaming & Standardization

| Original Column         | Cleaned Column        |
|-------------------------|-----------------------|
| `PatientId`             | `patient_id`          |
| `AppointmentID`         | `appointment_id`      |
| `Scheduled Day`         | `scheduled_day`       |
| `Scheduled Time`        | `scheduled_time`      |
| `Appointment Day`       | `appointment_day`     |
| `Appointment time`      | `appointment_time`    |
| `PateintAge` (typo)     | `patient_age`         |
| `Hipertension` (typo)   | `hypertension`        |
| `Handcap` (typo)        | `handicap`            |
| `No-show`               | `no_show`             |

- All column names were converted to **lowercase** with **underscores** for consistency (`snake_case`).
- Typographical errors were corrected.

---

### 🧪 Data Quality Fixes

- ✅ **Patient IDs** were converted from scientific/decimal format using power Query.
- ✅ **Age** with value `-1` was replaced with `0`
- ✅ **Checked for missing values** – none found
- ✅ **Checked for duplicates** – none found
- ✅ **Date & Time columns** (`scheduled_day`, `appointment_day`, `scheduled_time`, `appointment_time`) were formatted cleanly
- ✅ **Neighbourhood values** were reviewed and encoded properly (e.g., accented characters preserved)

---

## 💾 Output Files

- `medical_appointment.xlsx`  
  _(Fully cleaned version with proper formatting and standardized headers)_

---

## 📊 Column Descriptions

| Column Name         | Description |
|----------------------|-------------|
| `patient_id`         | Unique identifier for the patient |
| `appointment_id`     | Unique ID for the appointment |
| `gender`             | F or M |
| `scheduled_day`      | Date the appointment was scheduled |
| `scheduled_time`     | Time the appointment was scheduled |
| `appointment_day`    | Date of the actual appointment |
| `appointment_time`   | Time of the actual appointment |
| `patient_age`        | Age of the patient (0 to 115) |
| `neighbourhood`      | Neighborhood of the clinic |
| `scholarship`        | 1 if patient is enrolled in a social welfare program |
| `hypertension`       | 1 if patient has hypertension |
| `diabetes`           | 1 if patient has diabetes |
| `alcoholism`         | 1 if patient has alcoholism |
| `handicap`           | 0–4 scale for disability |
| `sms_received`       | 1 if a reminder SMS was sent |
| `no_show`            | "Yes" if patient missed the appointment, "No" otherwise |

---
##File contents
-Medical_appointments_no_show_cleaned.zip'-compressed archive containing the final excel file
   -format:'.xlsx'(Excel Workbook)
   -UTF-08
   -supports filters,formatting,Power Query transforming

## 📌 Notes

- No complex formulas or scripts were used.
- Cleaning focused on accessibility, structure, and clarity.
- The dataset is ready for analysis, dashboards, or further modeling.
- Download and unzip the file to avoid formatting issues
- 

---



**Chandini C**  


