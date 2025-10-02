# Teenage_Driving_and_Mortality
This project explores the causal effect of reaching the Minimum Legal Driving Age (MLDA) on mortality rates using Regression Discontinuity (RD) methods.


## Mortality Rate Comparison
- **Above MLDA (eligible to drive):**
  - All-cause mortality: 64.3 deaths / 100,000 person-years  
  - Motor vehicle mortality: 24.7 deaths / 100,000 person-years  
- **Below MLDA (not eligible):**
  - All-cause mortality: 34.1 deaths / 100,000 person-years  
  - Motor vehicle mortality: 9.37 deaths / 100,000 person-years  


## Scatter Plot
The scatter plot below shows mortality rates by age (measured in months from MLDA).  
- **Black squares:** all-cause mortality  
- **Blue circles:** motor vehicle accident mortality  
- **Vertical line:** MLDA threshold  

![Scatter Plot](Mortality%20Rates%20Before%20and%20After%20MLDA.png)

## RD Estimates
Both non-parametric and parametric “donut” RD estimates were calculated with bandwidths of 48, 24, 12, and 6 months.  
- Narrower bandwidths reduce bias but increase variance.  
- Parametric models with linear age trends produce smaller, more stable estimates than non-parametric RD.


## Files
- `all.dta`: Stata dataset  
- `Mortality Rates Before and After MLDA.png`: Scatter plot visualization  
- `README.md`: Project overview
