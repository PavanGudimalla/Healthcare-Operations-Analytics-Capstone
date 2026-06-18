# 🏥 OhioHealth Performance Metric Dashboard & Intervention Analytics

## 🎯 Executive Summary
This project evaluates the operational intervention process at OhioHealth to determine if current executive dashboard trigger logic effectively distinguishes meaningful performance issues from routine variation. By analyzing historical countermeasure records, this project successfully architected a shift from a reactive reporting model to a **signal-based decision framework**, significantly reducing administrative burden and optimizing operational outcomes.

## 🛠️ Analytical Approach & Methodology
* **Scale & Scope:** Processed and analyzed **1,296 site-metric-month observations** across 17 months of performance data to evaluate short-term operational responses.
* **KPI Evaluation:** Assessed **47 distinct metrics** across four critical balanced scorecard quadrants: Quality, Service, Finance, and Culture.
* **Statistical Modeling:** Deployed lagged regression testing and pattern testing to isolate and measure the short-term impact of formal interventions, controlling for site, metric, and temporal variables.

## 📊 Key Findings
* **Context is Everything:** System-wide testing revealed that interventions moved performance positively, but effects were highly dependent on timing. 
* **Target Proximity:** Interventions generated the highest ROI when performance was already close to the target, proving that early, data-driven action outperforms delayed, reactive measures.
* **The "Control Panel" Design:** Developed a decision-support framework utilizing trend direction, distance from target, and historical variability to categorize operational actions into clear, actionable states: *Monitor, Intervene, or Escalate*.

## 💡 Business & Strategic Impact
* **Reduced Administrative Waste:** Streamlined the Root Cause Analysis (RCA) pipeline by screening out routine statistical variations before assigning countermeasure work.
* **Actionable Intelligence:** Transformed a static monthly dashboard into a dynamic learning system that validates operational deterioration before committing leadership resources.
