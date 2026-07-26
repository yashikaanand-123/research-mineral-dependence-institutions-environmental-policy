# research-mineral-dependence-institutions-environmental-policy
Panel study of how government effectiveness moderates the impact of mineral dependence on environmental tax revenue across 63 countries (2003–2020).

# The Price of Ore: Institutions, Mineral Dependence & Environmental Policy

Panel study examining whether strong government institutions protect environmental tax policy from the pressures of mineral dependence.

## What I Built
- Country-year panel of 63 countries (2003–2020) with 1,134 observations
- Merged IMF Climate Indicators, World Bank WDI and WGI data
- OLS regressions with interaction terms and year fixed effects
- Machine-learning validation (Random Forest, AdaBoost, XGBoost) for feature importance
- Web-scraped EITI enforcement data (60,000+ mining penalty records) for supplementary analysis

## Key Findings
- Mineral dependence is associated with significantly lower environmental tax revenue (% of GDP)
- Government effectiveness substantially weakens this negative relationship
- Participatory institutions (Voice & Accountability) emerge as the strongest institutional predictor in ML models
- Strong institutions mitigate — but do not fully eliminate — the resource-curse effect on environmental fiscal policy

## Technologies Used
- Python (pandas, statsmodels, scikit-learn, XGBoost)
- Stargazer for regression tables
- Requests + API scraping (EITI SOE database)
- Matplotlib / Seaborn for visualization

## Skills Demonstrated
- Panel data construction and cleaning
- Econometric modeling (OLS, interactions, fixed effects)
- Machine-learning validation of econometric results
- Web scraping / API data collection
- Translating statistical findings into policy-relevant insights
