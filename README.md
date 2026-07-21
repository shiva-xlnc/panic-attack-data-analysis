# Panic Attack Data Analysis

An interactive Power BI dashboard analyzing patterns, triggers, and symptoms across 1,200 panic attack patient records — built to uncover relationships between demographics, lifestyle factors, and panic attack severity.

## 📌 Project Overview

This project explores a dataset of patient-level panic attack records to answer questions like:

- Which symptoms (dizziness, sweating, chest pain, trembling, shortness of breath) are most common among patients?
- How do panic scores vary across age groups (Adolescent, Adult, Senior)?
- What role do triggers — caffeine, phobia, PTSD, social anxiety — play in panic attack severity?
- Is there a relationship between sleep hours, alcohol consumption, and panic attack duration/frequency?
- How does medical history (anxiety, depression, PTSD) influence patient outcomes?

## 🗂️ Dataset

**File:** `panic_attack_dataset.xlsx`
**Records:** ~1,200 patients
**Columns include:**

| Column | Description |
|---|---|
| Age, Gender | Patient demographics |
| Panic_Attack_Frequency, Duration_Minutes | Frequency and length of attacks |
| Trigger | Caffeine, Stress, Phobia, PTSD, Social Anxiety |
| Heart_Rate | Recorded heart rate during an episode |
| Sweating, Shortness_of_Breath, Dizziness, Chest_Pain, Trembling | Symptom flags (Yes/No) |
| Medical_History | Anxiety, Depression, PTSD, None |
| Medication, Therapy | Treatment indicators |
| Caffeine_Intake, Alcohol_Consumption, Smoking, Exercise_Frequency, Sleep_Hours | Lifestyle factors |
| Panic_Score | Computed severity score |

## 📊 Dashboard Structure

The Power BI report (`Panic_Attack_Analysis.pbix`) is organized into 4 pages:

### 1. Panic Attacks (Cover Page)
Title page introducing the report.

![Panic Attacks Cover Page](screenshots/Panic%20Attack%20Cover.png)

### 2. No of Patients
Symptom-level breakdown showing how many patients experienced each symptom:
- Dizziness, Trembling, Chest Pain, Sweating, Shortness of Breath (True/False counts)

![No of Patients by Symptom](screenshots/No%20of%20Patients.png)

### 3. Other Requirements
Filterable view with slicers for **Panic Score**, **Gender**, **Trigger Reason**, and **Medical History**, alongside trend visuals for:
- Patients by Sleep Hours
- Patients by Panic Attack Duration
- Patients by Drinks Per Week

![Other Requirements - Filters and Trends](screenshots/Other%20Requirements.png)

### 4. Age Group Analysis
A comparative view of average Sleep Hours, Panic Score, and Panic Attack Frequency, segmented by **Trigger type** (Caffeine, Phobia, PTSD, Social Anxiety) and **Age Group** (Adolescent, Adult, Senior).

![Age Group Analysis](screenshots/Age%20Group%20Analysis.png)

## 🛠️ Tools Used

- **Power BI Desktop** — dashboard design and DAX measures
- **Power Query** — data transformation
- **Excel** — source dataset

## 🚀 How to Use

1. Clone or download this repository
2. Open `Panic_Attack_Analysis.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the slicers on the "Other Requirements" page to filter by gender, trigger, or medical history
4. Explore the Age Group Analysis page to compare severity patterns across life stages

## 📁 Repository Structure

```
panic-attack-data-analysis/
├── panic_attack_dataset.xlsx      # Source dataset
├── Panic_Attack_Analysis.pbix     # Power BI report
├── screenshots/
│   ├── Panic Attack Cover.png
│   ├── No of Patients.png
│   ├── Other Requirements.png
│   └── Age Group Analysis.png
└── README.md                      # Project documentation
```

## 📈 Key Insights (fill in once finalized)

- *e.g. Seniors with PTSD as a trigger show the highest average panic scores*
- *e.g. Sweating is the most commonly reported symptom across patients*
- *e.g. Higher caffeine intake correlates with increased panic attack frequency*

---

**Author:** Sai Shiva Varaprasad Gopu
