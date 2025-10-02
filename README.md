# SAS-Curiosity-Cup-2024

## 1. Project Overview  
This report analyzes electricity consumption patterns at La Trobe University’s Bundoora campus from 2018 to 2021, focusing on the impact of the COVID-19 pandemic and variations across building types such as libraries, offices, teaching, and mixed-use spaces. Using the UNICON dataset and SAS Viya for Learners, the study combines exploratory analysis and predictive modeling—including regression, decision trees, neural networks, and gradient boosting—to uncover key consumption drivers. Findings show that building type, academic calendar periods, and seasonal changes significantly influence energy use, with noticeable reductions during lockdowns and spikes during orientation and exam periods. The insights provide a data-driven foundation for La Trobe’s energy efficiency initiatives and its broader goal of achieving Net Zero Emissions by 2029.

## 3. Process Overview

### 3.1 Business Objective
La Trobe University is committed to achieving Net Zero Emissions by 2029. To support this, the business seeks to understand electricity consumption patterns across its Bundoora campus from 2018–2021, particularly before and during the COVID-19 pandemic.
- Identify significant trends in electricity consumption across different building types.
- Assess the impact of COVID-19 restrictions and university events on consumption.
- Provide insights to inform energy efficiency projects (e.g., solar panels, LED installations).

### 3.2 Scope
- Timeframe: 2018–2021
- Data Source: UNICON dataset (open source, La Trobe University)
- Focus Buildings: Library, Office, Teaching, and Mixed-use

### 3.3 Business Requirements
- Understand historical electricity consumption patterns at Bundoora campus (2018–2021).
- Assess the impact of COVID-19 and academic events on energy usage.
- Identify the building types and factors that most influence electricity consumption.
- Support La Trobe University’s Net Zero Emissions by 2029 strategy with actionable insights.

### 3.4 Success Criteria
- Clear visualizations and reports showing consumption trends across years and building types.
- Predictive models with acceptable accuracy (e.g., ASE < 0.1 for Gradient Boosting).
- Identification of at least 3–5 key factors influencing energy consumption.
- Recommendations aligned with La Trobe’s sustainability strategy, such as targeted interventions for high-consumption buildings

## 4. User stories and Acceptance criteria
User Story 1:
As a Facilities Manager, I want to view monthly electricity consumption patterns so that I can plan energy-saving measures.

✅ Acceptance: Dashboard shows monthly trends across all building types.

User Story 2:
As a Sustainability Officer, I want to compare pre-COVID and COVID-era usage so that I can assess behavioral impacts.

✅ Acceptance: Report highlights percentage drop in consumption during 2020 lockdowns.

User Story 3:
As an Analyst, I want to identify which building types contribute most to energy consumption so that I can recommend interventions.

✅ Acceptance: Predictive model outputs top 5 factors influencing consumption (mixed, library, office, teaching, month).

User Story 4:
As a University Leadership Team member, I want forecasts of future energy consumption so that I can align sustainability projects.

✅ Acceptance: Model projections provided with confidence intervals and clear visualizations.

## 5. Flowchart
<img width="424" height="768" alt="analytics_flowchart_refined" src="https://github.com/user-attachments/assets/f61c065c-22ef-49da-8b71-d1dc0ffbb14f" />


## 6. Feedback and Contributions  
This project was created as part of my **data analytics portfolio** to demonstrate skills in data visualization, business insights, and storytelling with Power BI.  

- Feedback, suggestions, and pull requests are welcome.  
- If you’d like to collaborate on extending this project feel free to open an issue or reach out.

## 7. References
La Trobe University. (2024). Our journey so far. https://www.latrobe.edu.au/sustainability/net-zero/our-journey-so-far

Li, Y., Wang, W., Wang, Y., Xin, Y., He, T., & Zhao, G. (2020). A review of studies involving the effects of climate change on the energy consumption for building heating and cooling.
International Journal of Environmental Research and Public Health, 18(1), 1–18. https://www.mdpi.com/1660-4601/18/1/40

Malakoutian, M. A., Malakoutian, Y., Mostafapoor, P., & Amjadi, M. (2021). Correlation Between Energy Consumption and Building Size. ENG Transactions, 2, 1-6.

Oakman, J., Kinsman, N., Graham, M., Stuckey, R., & Weale, V. (2022). Strategies to manage working from home during the pandemic: the employee experience. Industrial Health, 60(4), 319–333. https://www.jstage.jst.go.jp/article/indhealth/60/4/60_2022-0042/_article

Raza, S. A., Shah, N., & Sharif, A. (2019). Time frequency relationship between energy consumption, economic growth, and environmental degradation in the United States: Evidence from transportation sector. Energy, 173, 706-720.

Sharma, A., & Kumar, H. (2019). Seasonal variation on electricity consumption of academic building-a case study. Journal of Thermal Energy System, 2(2), 1-6.

Zhang, C., Liao, H., & Mi, Z. (2019). Climate impacts: temperature and electricity consumption. Natural Hazards (Dordrecht), 99(3), 1259–1275. https://doi.org/10.1007/s11069-019-03653-w

---

