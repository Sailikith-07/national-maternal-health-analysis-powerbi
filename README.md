# National Maternal Health Analysis: Barriers to Institutional Delivery
# Background and Overview

Institutional delivery is a cornerstone of maternal healthcare, yet a significant challenge persists: **approximately 20% of deliveries in designated critical districts still occur outside of medical facilities**. While national infrastructure initiatives have expanded access, the mere presence of buildings does not guarantee utilization.

**Project Goals:**
- Conduct a Root Cause Analysis (RCA) to identify the "hidden bottlenecks" deterring expectant mothers from utilizing institutional care.
- Analyze the shift in delivery trends from 2015 to a 2023 forecast.
- Evaluate the Equity Gap between Aspirational and Standard districts to measure the success of targeted interventions.
- Assess the impact of Service Continuity and Financial Protection on final birth outcomes.

An Interactive Power BI Report can be downloaded **here**
A PPT presentation provides a clear and detailed explanation of the project is **here**

--

# Data Structure Overview

The analysis utilizes a multi-dimensional dataset focused on maternal health indicators across **700+** districts in India.

![Data Model](https://github.com/Sailikith-07/national-maternal-health-analysis-powerbi/blob/main/Images/Data%20Model.png)

- **Time Dimensions:** Longitudinal data covering 2015, 2019, and projected 2023 targets.

- **Demographic Segments:** State-level audits (Top Performers vs. Priority States) and District classifications (Aspirational vs. Standard).

- **Key Metrics:** Institutional Birth (IB) Rate, 4+ Antenatal Care (ANC) visits, Out-of-Pocket (OOP) Expenditure, and Facility Density (PHCs/Sub-Centers).

--

# Executive Summary

After gaining **8.69%** growth in institutional births since 2015, the national average reached **87.5%** in 2019. While the trajectory is positive—projecting a **96.21% rate by 2023**—significant regional disparities remain.

**Top Finding:** True access extends beyond building facilities. Our analysis reveals that **Service Continuity (ANC completion)** and **Financial Protection (reducing OOP costs)** are the primary drivers of hospital utilization. Infrastructure only acts as an enabler when it is functional and physically proximate to the mother.

Below is the Summary Report of this project, this dashboard also includes diagnostic analysis. The enitre interactive dashboard can be downloaded **here**

![Suammry Report](https://github.com/Sailikith-07/national-maternal-health-analysis-powerbi/blob/main/Images/Summary%20Report.png)

--

# Insights Deep Dive

**1. The Financial Deterrent: High Cost of "Free" Healthcare**

**Finding:** There is an inverse correlation between Out-of-Pocket (OOP) costs and hospital deliveries.

**Data:** High travel costs and incidental hospital fees act as a "regressive tax" on vulnerable families.

**Impact:** Even with "free" public schemes, hidden costs deter families from seeking medical attention.

![Avg Out of Pocket Expenditure](https://github.com/Sailikith-07/national-maternal-health-analysis-powerbi/blob/main/Images/Avg%20out%20of%20pocket.png)

**2. The Service Barrier: The "ANC Drop-off"**

**Finding:** Registration (MCP Card) is high, but retention is low.

**Data:** There is a significant decline in mothers completing the required 4 ANC visits.

**Impact:** This "lost contact" at a critical juncture is a primary failure point for institutional delivery.

![ANC Coverage](https://github.com/Sailikith-07/national-maternal-health-analysis-powerbi/blob/main/Images/ANC%20Coverage.png)

**3. The Infrastructure Bottleneck**

**Finding:** Physical proximity is the primary enabler.

**Data:** Lower facility density correlates with a decline in ANC visits.

**Evidence:** Functional Primary Health Centers (PHCs) drive the coverage needed for mothers to commit to hospital births.

![District-wise Performance Indicators](https://github.com/Sailikith-07/national-maternal-health-analysis-powerbi/blob/main/Images/District%20PIs.png)

--

# Caveats and Assumptions

To ensure the integrity of this analysis, the following limitations and assumptions must be noted:

**Linear Projection Assumption:** The 2023 forecast assumes a linear continuation of progress seen between 2015 and 2019. It does not account for major external shocks (like the long-term impact of COVID-19 on healthcare infrastructure).

**Data Lag:** The analysis relies on NFHS-4 and NFHS-5 data. Real-time changes in district-level infrastructure since 2021 may not be fully reflected.

**Self-Reporting Bias:** Metrics such as "Out-of-Pocket Expenditure" are based on survey responses, which may be subject to recall bias by the participants.

**Functional vs. Physical:** A "Functional PHC" is defined by the presence of staff and equipment as per the RHS; however, the actual quality of care provided during a visit is not quantified in this dataset.

**Limited Data for Root Cause Analysis:**
While performing 5‑Why analysis on ANC coverage, the investigation could only proceed two levels before data gaps appeared. Information on functional aspects such as availability of qualified doctors, medical equipment, or sub‑center readiness was not present. As a result, deeper diagnostic insights could not be established.

--

# Recommendations

**1. Functionalize Existing Infrastructure**
   
**Action:** Shift focus from new construction to making existing Sub-Centers functional as "Health and Wellness Centers".

**Goal:** Ensure every district has a functional PHC that can provide consistent ANC services.

**2. Implement a Service Continuity Model**

**Action:** Use MCP card registrations not just as a record, but as a tracking and "nudge" system.

**Goal:** Proactively follow up with mothers who miss their 3rd or 4th ANC visit to prevent "lost contact".

**3. Expand Financial Protection Mechanisms**

**Action:** Expand cashless schemes beyond the delivery itself to cover transportation and incidental medicines.

**Goal:** Remove the economic "regressive tax" that prevents families from utilizing public facilities.

--

# Author & Contact

**Gundeti Sailikith**

Aspiring Data Analyst

📧 Email: gundetisalikith@gmail.com

🔗 [LinkedIn](https://www.linkedin.com/in/sailikith-gundeti/)
