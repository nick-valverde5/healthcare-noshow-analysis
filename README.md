# Healthcare No-Show Appointment Analysis

## Project Overview
This project analyzes 110,000+ real medical appointment records to identify 
patterns in patient no-shows and provide actionable recommendations for 
healthcare organizations to improve attendance rates.

---

## Business Problem
No-show appointments cost healthcare organizations time and money while 
reducing access to care for other patients. This analysis identifies which 
patient groups are highest risk and why.

---

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- GitHub

---

## Dataset
- 110,522 medical appointments from Brazil (2016)
- Source: Kaggle — Medical Appointment No Shows
- Features include: age, gender, neighbourhood, chronic conditions, 
  SMS reminders, and no-show status

---

## Key Questions Answered
1. Does receiving an SMS reminder reduce no-shows?
2. Do patients who wait longer tend to no-show more?
3. Which age group no-shows the most?
4. Do chronic condition patients attend more reliably?
5. Which neighbourhoods have the highest no-show rates?

---

## Key Findings
Overall

No-show rate: 20.2% — 1 in 5 patients missed their appointment

SMS Reminders

Patients who received SMS had higher no-show rates (27.6% vs 16.7%) — not because reminders backfire, but because they were likely sent to high-risk, long-wait patients in the first place

Wait Time

Same-day appointments: only 6.6% no-show rate
31–90 day waits: 33.2% no-show rate — longer the wait, higher the risk

Age

Young adults (19–35) had the highest no-show rate at 23.8%

Chronic Conditions

Patients with hypertension showed up at 82.7% (17.3% no-show)
Patients with diabetes showed up at 82.0% (18.0% no-show) — both more reliable than average

High-Risk Neighbourhoods

Santos Dumont (28.9%), Santa Cecília (27.5%), Santa Clara (26.5%)
