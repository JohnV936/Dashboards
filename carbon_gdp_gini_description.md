The Carbon_gdp_gini.R and Carbon_gdp_gini.pbix dashboards take data imported from https://ourworldindata.org.
They are intended to be the same dashboard in two different tools. 
The raw data is timeseries values for Carbon Footprint per Capita (CF_pc), 
Gross Domestic Product per Capita (GDP_pc) and Gini Index (GI).
They have three tabs. 
Tab 1:
One shows trends from 1980-2020 in CF_pc, GDP_pc and GI for a user selected country.
Tab 2:
The second shows a colour map of correlation coefficients 
between GDP per capita and carbon_footprint per capita.
Tab 3:
The third tab shows an automated ARIMA forecast of for all three quantities for a user 
specified country and a user specified number of years into the future.

Notes for interpretting results:
1. The raw data used imputed values so only the general trends are accurate.
They are not suitable for accurate numerical prediction.
2. Many of the ARIMA forecasts, as shown in the visualisation,
fail some of the ARIMA assumptions. The full impact of this on the forecast would
need more rigorous analysis
