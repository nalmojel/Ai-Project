## Research Context

This project was developed alongside a comprehensive literature review of 7 peer-reviewed 
climate science papers, identifying key gaps in existing research:

- Most existing studies rely on limited data sources — this project addresses that by 
  analysing 250+ years of records across 243 countries
- Current research uses outdated statistical methods — this project applies ML-based 
  predictive modelling as an improvement
- Existing models lack regional granularity — this project identifies priority regions 
  with the highest temperature increases

## Key Contributions

- **Enhanced Data Processing** — built a preprocessing pipeline using two missing value 
  strategies (removal vs. mean imputation by country) to maximise data retention while 
  maintaining statistical validity
- **Historical Trend Analysis** — comprehensive time-series analysis of long-term 
  climate behaviour from the 1850s to present
- **Regional Pattern Identification** — identified regions with the most significant 
  temperature changes, useful for climate policy prioritisation
- **Seasonal Variation Analysis** — quantified seasonal temperature differences to 
  support climate change adaptation models
- **Predictive Modelling** — linear regression forecasting framework serving as a 
  reference for both research and policy planning

## Key Findings

- Global average land temperatures have risen steadily since the 1850s baseline
- Identified the top 10 countries with the highest recorded temperature increases
- Mean imputation by country produced cleaner trend lines than row removal, 
  better preserving regional climate variation
- Predictive model projects continued warming if current trends persist, 
  consistent with the 1.5–2°C thresholds discussed in IPCC literature

## Academic Report

This project was completed with a full literature review and academic report.  
📄 [View the Literature Review Report](./cs316_phase_2_2__1_.pdf)
