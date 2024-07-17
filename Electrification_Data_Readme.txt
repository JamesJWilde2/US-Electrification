Electrification Data Readme

Files
-----


`county_place_criteria.csv` : various criteria for each county and census incorperated place (CIP)
* `GEOID` (str) : Unique Identifier for County or Place. Counties have 5 Digit GEOIDs (2 Digit State + 3 Digit County). Places have 7 digits GEOIDs (2 Digit State + 5 Digit Place).
* `Name` (str): Name of the County or CIP.
* `State_abbr` (str): Two letter state postal abbreviation.
* `Spatial_Level` (str): "County" or "Place".
* `Heating_Delivered_Fuel` (int) :  Number of occupied housing units heated with delivered fuel (fuel oil, propane or kerosene).
* `Heating_Electric` (int) :  Number of occupied housing units heated with electric heating (electric resistance baseboard, electric furnace, or heat pump).
* `Division_Electric_Pct_Heat_Pump` (float) : Proportion of electrically heated occupied housing units that are heated with heat pumps (statistics is at the census division level).
* `Energy_Burden_Pct_Income` (float) : Average proportion of household income spent on energy bills.
* `hvac_energy_intensity` (float) : Average household HVAC energy consumption per sqft (kBTU / ft2). Includes only heating and cooling end uses, not including dwelling units heated by heat pumps. 
* `upgrade_annual_spend_delta` (float) : Difference between annual energy bills before and after electrification for all households. 
* `kg_co2e_emissions_saved` (float) : Difference between annual household emissions (kg CO2e / yr) before and after electrification for all housing units. 
* `Total_New_Units` (float) : Number of newly constructed housing units per year. 
* `Residential_Solar_Generation_Potential` (float) : The estimated technical generation potential of residential rooftop solar for all households (MWh).
* `Pct_Solar_Install` (float) : Proporton of occupied housing units with rooftop solar.


`county_place_population_2020.csv` : 2020 populations of each county and place
* `GEOID` (str) : Unique Identifier for County or Place. Counties have 5 Digit GEOIDs (2 Digit State + 3 Digit County). Places have 7 digits GEOIDs (2 Digit State + 5 Digit Place).
* `Spatial_Level` (str): "County" or "Place".
* `Total_Population` : Total number of people according to 2020 Census
* `Total_Households` : Total number of households according to 2020 Census


Notes: 
-----
* The terms "occupied housing units' and 'household' are interchangable
* Some housing unit count features are floats because they were computed by apportionment from different spatial units
* All criteria statistics are from between 2018 - 2021







