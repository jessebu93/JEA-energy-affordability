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

data/raw/dewey/dewey_jea_service_area.dta: 
This dataset contains parcel-level property assessment and housing characteristic data for properties located in the Florida counties served entirely or in part by JEA: Duval, Clay, St. Johns, and Nassau. The data come from Dewey property records and reflect property assessment, ownership, tax, sale, and structural characteristics from year XXXX.

This dataset is used in the project to obtain key property and household-relevant characteristics for the JEA sample. These include location, market value, assessed value, tax burden, tax delinquency, owner occupancy, exemptions, housing size, housing age, HVAC characteristics, and amenities. County is identified using SITUSSTATECOUNTYFIPS. 

LATITUDE: Latitude of the property location.                                            
LONGITUDE: Longitude of the property location.                                                  
PROPERTYADDRESSFULL: Full property situs address.                                                                    
PROPERTYADDRESSCITY: City from the property address.                                                      
PROPERTYADDRESSSTATE: State from the property address.                                                     
PROPERTYADDRESSZIP: ZIP code from the property address.                                                  
PROPERTYADDRESSZIP4: ZIP+4 extension from the property address.                                           
SITUSSTATECOUNTYFIPS: State and county FIPS code for the property location.                                           
CENSUSTRACT: Census tract identifier associated with the property location.                                  
CENSUSBLOCKGROUP: Census block group identifier associated with the property location.                            
CENSUSBLOCK: Census block identifier associated with the property location.                                  
TAXMARKETVALUETOTAL: Total market value of the property for tax assessment purposes.                       
TAXASSESSEDVALUETOTAL: Total assessed value of the property for tax purposes.                                          
TAXBILLEDAMOUNT: Total property tax amount billed.                                                               
TAXDELINQUENTYEAR: Year associated with property tax delinquency, if any.                                          
TAXFISCALYEAR: Fiscal year associated with the tax record.                                                     
TAXYEARASSESSED: Year in which the property was assessed for tax purposes.                                       
TAXMARKETVALUEYEAR: Year associated with the reported market value.                                                 
TAXRATEAREA: Tax rate area or jurisdiction code associated with the property.                                
TAXEXEMPTIONHOMEOWNERFLAG: Indicator for whether the property has a homeowner exemption.                                   
TAXEXEMPTIONSENIORFLAG: Indicator for whether the property has a senior exemption.                                      
TAXEXEMPTIONVETERANFLAG: Indicator for whether the property has a veteran exemption.                                     
TAXEXEMPTIONDISABLEDFLAG: Indicator for whether the property has a disability exemption.                          
TAXEXEMPTIONWIDOWFLAG: Indicator for whether the property has a widow exemption.                            
STATUSOWNEROCUPIEDFLAG: Indicator for whether the property is classified as owner-occupied.                             
OWNERTYPEDESCRIPTION1: Description of the owner type, such as individual, company, trust, or other ownership category. 
OWNERSHIPVESTINGRELATIONCODE: Code describing the legal ownership or vesting relationship.                                    
COMPANYFLAG: Indicator for whether the owner appears to be a company or business entity.                     
CONTACTOWNERMAILADDRESSFULL: Full mailing address for the property owner.                                                    
AREABUILDING: Building area, typically measured in square feet.                                               
AREAGROSS: Gross building area, typically measured in square feet.                                         
AREA1STFLOOR: Area of the first floor of the structure.                                                       
AREA2NDFLOOR: Area of the second floor of the structure.                                                      
AREAUPPERFLOORS: Area of upper floors beyond the first floor.                                                    
BUILDINGCOUNT: Number of buildings or structures associated with the property.                                 
UNITSCOUNT: Number of residential or property units associated with the parcel.                             
BEDROOMSCOUNT: Number of bedrooms reported for the property.                                                   
BATHCOUNT: Number of bathrooms reported for the property.                                                  
BATHPARTIALCOUNT: Number of partial bathrooms reported for the property.                                          
ROOMSCOUNT: Total number of rooms reported for the property.                                                
STORIESCOUNT: Number of stories or floors in the structure.                                                   
YEARBUILT: Year the structure was originally built.                                                        
YEARBUILTEFFECTIVE: Effective year built, which may reflect major renovations or updates.                           
STRUCTURESTYLE: Coded or text description of the structure style.                                               
CONSTRUCTION: Coded or text description of the construction type.                                             
FOUNDATION: Coded or text description of the foundation type.                                               
ROOFMATERIAL: Coded or text description of the roof material.                                                 
ROOFCONSTRUCTION: Coded or text description of roof construction.                                                 
HVACCOOLINGDETAIL: Coded description of the cooling system or air conditioning type.                               
HVACHEATINGDETAIL: Coded description of the heating system type.                                                   
HVACHEATINGFUEL: Coded description of the heating fuel type.                                                     
TOPOGRAPHYCODE: Code describing the topography or physical land characteristics of the property.                
DEEDLASTSALEDATE: Date of the most recent recorded deed sale or transfer.                                         
DEEDLASTSALEPRICE: Sale price associated with the most recent recorded deed sale.                                  
ASSESSORLASTSALEDATE: Date of the most recent sale recorded in assessor data.                                        
ASSESSORLASTSALEAMOUNT: Sale amount associated with the most recent assessor-recorded sale.                             
ASSESSORPRIORSALEDATE: Date of the prior sale recorded in assessor data.                                               
ASSESSORPRIORSALEAMOUNT: Sale amount associated with the prior assessor-recorded sale.                                   
LASTOWNERSHIPTRANSFERDATE: Date of the most recent ownership transfer.                                                     
POOL: Indicator for whether the property has a pool.                                                  
POOLAREA: Area of the pool, if reported.                                                                  
POOLHOUSEAREA: Area of the pool house, if reported.                                                            
PARKINGGARAGE: Indicator or category for whether the property has garage parking.                              
PARKINGGARAGEAREA: Area of garage parking, if reported.                                                            
PARKINGCARPORT: Indicator or category for whether the property has a carport.                                   
PARKINGSPACECOUNT: Number of parking spaces reported for the property.                                             
FIREPLACE: Indicator for whether the property has a fireplace.                                             
FIREPLACECOUNT: Number of fireplaces reported for the property.                                                 
SPRINKLERSFLAG: Indicator for whether the property has sprinklers.                                              


