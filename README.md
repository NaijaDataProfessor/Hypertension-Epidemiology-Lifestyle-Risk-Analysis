# Hypertension Epidemiology & Lifestyle Risk Analysis

## Project Overview
Hypertension remains one of the most persistent and preventable contributors to cardiovascular morbidity worldwide. This project analyzes patient-level clinical and behavioral data to identify demographic, hereditary, and lifestyle drivers associated with hypertension prevalence and treatment gaps.

The goal is to uncover actionable insights that support early risk detection and inform targeted public health and clinical interventions.

---

## Dataset Summary
- Total Patients Analyzed: **1,985**
- Hypertensive Patients: **1,032**
- Non-Hypertensive Patients: 953

---

## Key Objectives
- Measure hypertension prevalence  
- Identify demographic segments most affected  
- Evaluate the role of family history  
- Assess lifestyle patterns among hypertensive patients  
- Examine treatment coverage among diagnosed patients  

---

## Analytical Approach
The analysis was performed using SQL to segment patient data across multiple dimensions:
- Age grouping  
- Genetic predisposition (family history)  
- Lifestyle factors (BMI, smoking, exercise, salt intake, sleep, stress)  
- Medication usage  

---

## Key Findings

### 1. Hypertension Prevalence
Out of 1,985 patient records analyzed, 1,032 were hypertensive (**51.99% prevalence**), indicating hypertension is highly dominant in this cohort.

---

### 2. Age Distribution of Hypertensive Patients

| Age Group     | Patients | Share |
|--------------|---------|-------|
| Senior       | 461 | 44.7% |
| Adult        | 336 | 32.6% |
| Young Adult  | 148 | 14.3% |
| Youth        | 87 | 8.4% |

Hypertension rises sharply with age, yet **22.7%** of cases occur below 37 years, signaling early-onset risk.

---

### 3. Family History Influence

| Family History | Hypertensive Patients | Share |
|---------------|----------------------|-------|
| Yes           | 652 | 63.2% |
| No            | 380 | 36.8% |

Genetic predisposition is a strong contributor to hypertension risk.

---

### 4. Lifestyle Patterns Among Hypertensive Patients
Common characteristics across hypertensive groups:
- Overweight BMI (26+)  
- High salt intake (~8.5–9)  
- Short sleep duration (~6 hours)  
- Elevated stress levels  

Exercise alone did not significantly offset hypertension risk when other lifestyle factors remained unfavorable.

---

### 5. Treatment Coverage

| Status | Patients | Share |
|--------|----------|-------|
| On Medication | 620 | 60.1% |
| Untreated | 412 | 39.9% |

Beta blockers were the most prescribed drug class. A large untreated hypertensive population suggests a care gap.

---

## Tools Used
- SQL (Data analysis & segmentation)  
- Structured clinical dataset  
- GitHub (documentation and version control)  

---

## Project Significance
This analysis highlights that hypertension in the study population is:
- Highly prevalent  
- Strongly age- and genetics-driven  
- Reinforced by lifestyle risk factors  
- Under-treated in a significant portion of patients  

The findings support the need for:
- Early screening among younger adults  
- Lifestyle-centered interventions  
- Improved treatment adherence and accessibility  

