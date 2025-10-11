| [home page](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/) | [Visualizing Government Debt](dataviz-examples) | [Critique and redesign (MakeoverMonday)](protein-viz) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Outline

## High-Level Summary
This project focuses on predicting and explaining the deterioration of protective coatings on steel bridges, with emphasis on Element 515 condition ratings from the National Bridge Inventory (NBI). Protective coatings are essential for preventing corrosion and extending bridge service life. However, deterioration rates vary widely depending on location, environment, and traffic exposure, which makes it difficult for owners to plan maintenance and repainting efficiently.  

The goal of this project is to estimate the expected lifetime of protective coatings and to identify outlier bridges where coatings are failing faster than expected. By using publicly available NBI data, this analysis will provide insights into which factors—such as traffic, age, design, and environmental conditions—best predict coating condition over time. Ultimately, the work will support decision-making for bridge owners and policymakers, helping them prioritize repainting schedules, optimize budgets, and reduce lifecycle costs.  

## Project Structure (Story Arc)
1. **Introduction / Context**  
   Importance of protective coatings for steel bridges and the challenge of deterioration monitoring.  
2. **Problem Statement**  
   Owners struggle to predict coating service life, resulting in costly premature repainting or risky delays.  
3. **Data Foundation**  
   Introduce NBI structure-level and element-level datasets, especially Element 515. Highlight key variables such as year built, average daily traffic (ADT), and design codes.  
4. **Exploratory Insights**  
   Visualize deterioration patterns in Pennsylvania as the starting case study. Show distribution of condition states and maps of bridge locations.  
5. **Feature Development**  
   Build engineered features: bridge age, traffic exposure, environmental proxies (urban vs rural, freeze–thaw cycles, coastal proximity).  
6. **Predictive Modeling**  
   Apply baseline regressions and survival analysis to estimate “time-to-repaint.” Include outlier detection to flag bridges degrading faster than predicted.  
7. **Insights & Implications**  
   Discuss how the model can inform repainting schedules and regional planning. Provide case studies of flagged outliers.  
8. **Conclusion**  
   Summarize the value of data-driven coating life prediction for cost savings and infrastructure resilience.  

**One-Sentence Summary**  
Predicting the service life of steel bridge protective coatings using NBI data to help owners prioritize repainting and reduce maintenance costs.  

**User Stories**  
- As a **bridge owner**, I want reliable indicators of coating deterioration so that I can plan repainting efficiently.  
- As an **engineer/inspector**, I want to understand which factors accelerate coating failure to improve maintenance practices.  
- As a **policy planner**, I want to compare performance across regions to better allocate funding and resources.  

---

## Initial sketches

Two interactive sketches are embedded below.

**Sketch 1 — PA 2025: Conditional hierarchical map (more layers)）**  
<iframe src="./pa2025_map_plus.html" width="100%" height="620" style="border:1px solid #ccc;border-radius:6px;"></iframe>  
<small> <a href="./pa2025_map_plus.html">pa2025_map_plus.html</a></small>

**Sketch 2 — Prediction vs. Observation Comparison Chart (Bubble + Stroke)**  
<iframe src="./pa2025_map_pred_vs_obs.html" width="100%" height="620" style="border:1px solid #ccc;border-radius:6px;"></iframe>  
<small> <a href="./pa2025_map_pred_vs_obs.html">pa2025_map_pred_vs_obs.html</a></small>

---

# The data

The project will use publicly available datasets from the National Bridge Inventory (NBI). Two primary sources are:  

1. **NBI General Data** – Contains structure-level information such as state codes, latitude/longitude, year built, number of lanes, and average daily traffic. These variables provide the context for bridge use and environment.  
2. **NBI Element-Level Data** – Focused on Element 515 (steel protective coatings), which records coating condition states (1–4) and the square footage of each condition per bridge per year. This dataset forms the foundation of the deterioration analysis.  

The initial scope will focus on Pennsylvania, 2025 (CSV provided), with the option to expand to earlier years and additional states once the data pipeline is established. Using these datasets, we will clean, join, and normalize records by bridge ID and coated area. The data will then be used for exploratory analysis, feature engineering, and predictive modeling of coating service life.  

| Name | URL | Description |
|------|-----|-------------|
| National Bridge Inventory (General) | [https://www.fhwa.dot.gov/bridge/nbi.cfm](https://www.fhwa.dot.gov/bridge/nbi.cfm) | Structure-level bridge information: ID, location, design, traffic, year built |
| National Bridge Inventory (Element-Level) | [https://infobridge.fhwa.dot.gov](https://infobridge.fhwa.dot.gov) | Element 515 condition data including protective coating deterioration |
| Pennsylvania 2025 CSV (Provided) | [(link to GitHub)](https://github.com/Aspdelus/Aspdelus-dataviz-portfolio/blob/main/PA%20Bridge%20Site%202025.csv) | State-specific dataset for pilot analysis |

---

# Method and medium

This project will be developed using a combination of **Tableau** (for visualization) and **Shorthand** (for storytelling and interactive presentation). Tableau will allow us to create maps, scatterplots, survival curves, and feature importance graphics. Shorthand will be used to structure the narrative, integrate visuals, and make the final project interactive and accessible to the target audience.  

The final deliverable will be a GitHub-hosted page with interactive visualizations embedded, providing both technical insights and an engaging narrative.

---

## References
- National Bridge Inventory, Federal Highway Administration.  
- AASHTO, *Specifications for the National Bridge Inventory Elements*.  
- *Good Charts*, Scott Berinato, Chapters 5–6, 8.

---

**Navigation:**  
[← Previous: Critique by Design](protein-viz) | [Back to Home](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/) | [Next: Part II →](final-project-part-two)  

