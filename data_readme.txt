raw/rates/electricity_rates_JEA_2019_2026:
This dataset contains residential electricity rate information for JEA from January 2019 through June 2026. It includes the main components used to calculate customer bills: a fixed basic charge, a tiered energy rate (per kWh) with separate rates for consumption below and above 1,000 kWh, a fuel charge (per kWh) that reflects a full pass-through of JEA’s electricity generation costs, and an environmental charge (per kWh) that was in effect until March 2023. The dataset also includes the applicable tax rates for each county served by JEA over the full period. For the fuel charge, only 5.11 cents per kWh are taxable. 

The dataset was constructed using JEA’s official rates website (https://www.jea.com/rates/) and archived versions of that website accessed through the Wayback Machine. These sources were supplemented with JEA Board Meeting packages (https://www.jea.com/about/board_and_management/board_meetings_archive/), tariff sheets, and bill breakdown documents (https://www.jea.com/My_Account/Understand_My_Bill/Bill_Breakdown/), which were also obtained through JEA’s website and archived versions available through the Wayback Machine.

This dataset is used in the project to reconstruct individual customer electricity bills over time. By combining customers’ electricity consumption with the applicable rate components and county-specific tax rates, the project can estimate monthly bills consistently across the study period.


Var list:
year: The calendar year the rate applies to.
month: The calendar month the rate applies to.
base_rate: Fixed monthly customer charge, regardless of electricity usage.
energy_rate_less_than_1000kWh: Energy charge in USD per kWh for usage up to 1,000 kWh.
energy_rate_more_than_1000kWh: Energy charge in USD per kWh for usage above 1,000 kWh.
fuel_rate_total: Total fuel charge applied per kWh.
fuel_rate_taxable: Portion of the fuel charge that is subject to tax.
environmental_rate: Environmental charge applied per kWh.
total_rate_tier1: Total per-kWh rate for Tier 1 usage (up to 1,000 kWh).
total_rate_tier2: Total per-kWh rate for Tier 2 usage (above 1,000 kWh).
duval_county_tax_rate: Applicable tax rate for customers in Duval County.
atlantic_beach_tax_rate: Applicable tax rate for customers in Atlantic Beach.
baldwin_tax_rate: Applicable tax rate for customers in Baldwin.
clay_county_tax_rate1: Applicable tax rate for customers in Clay county for usage below 500kWh.
clay_county_tax_rate2: Applicable tax rate for customers in Clay county for usage above 500kWh.
orange_park_tax_rate: Applicable tax rate for customers in Orange Park.
stjohns_county_tax_rate1: Applicable tax rate for customers in St Johns county for usage below 500kWh.
stjohns_county_tax_rate2: Applicable tax rate for customers in St Johns county for usage above 500kWh.


raw/rates/water_rates_JEA_2019_2026:
This dataset contains residential water and sewer rate information for JEA from January 2019 through June 2026. It includes the main components used to calculate customer bills: tiered water consumption rates based on kGal usage, fixed water charges that vary by meter size, sewer consumption rates, and fixed sewer charges that also vary by meter size.

The dataset was constructed using JEA’s official rates website (https://www.jea.com/rates/; https://www.jea.com/My_Account/Rates/Water_and_Sewer_Tariff/) and archived versions of that website accessed through the Wayback Machine. These sources were supplemented with JEA Board Meeting packages (https://www.jea.com/about/board_and_management/board_meetings_archive/) and bill breakdown documents (https://www.jea.com/My_Account/Understand_My_Bill/Bill_Breakdown/), which were also obtained through JEA’s website and archived versions available through the Wayback Machine.

This dataset is used in the project to reconstruct individual customer water and sewer bills over time. By combining customers’ water consumption with the applicable water and sewer rate components and county-specific tax rates, the project can estimate monthly bills consistently across the study period.


 year: The calendar year the rate applies to.              
 month: The calendar month the rate applies to.             
 water_rate_1_4: Water usage rate for the 1–4 usage tier.            
 water_rate_5_6: Water usage rate for the 5–6 usage tier.            
 water_rate_7_8: Water usage rate for the 7–8 usage tier.            
 water_rate_9_15: Water usage rate for the 9–15 usage tier.           
 water_rate_15_20: Water usage rate for the 15–20 usage tier.          
 water_rate_20: Water usage rate for usage above 20.                
 environmental_rate_water: Environmental charge applied to water service.      
 water_meter_size1: Fixed water meter charge for a ⅝-inch meter.        
 water_meter_size2: Fixed water meter charge for a ¾-inch meter.        
 water_meter_size3: Fixed water meter charge for a 1-inch meter.        
 water_meter_size4: Fixed water meter charge for a 1 ½-inch meter.      
 water_meter_size5: Fixed water meter charge for a 2-inch meter.        
 sewer_rate_tier1: Sewer usage rate for Tier 1 usage.                  
 sewer_rate_tier2: Sewer usage rate for Tier 2 usage.                  
 environmental_rate_sewer: Environmental charge applied to sewer service.      
 sewer_meter_size1: Fixed sewer meter charge for a ⅝-inch meter.        
 sewer_meter_size2: Fixed sewer meter charge for a ¾-inch meter.        
 sewer_meter_size3: Fixed sewer meter charge for a 1-inch meter.        
 sewer_meter_size4: Fixed sewer meter charge for a 1 ½-inch meter.      
 sewer_meter_size5: Fixed sewer meter charge for a 2-inch meter.        
 duval_county_tax_rate_water: Applicable Duval County tax rate for water service. 
 duval_county_tax_rate_sewer: Applicable Duval County tax rate for sewer service. 
