# Exploring Relationships between Criteria Air Pollutants, Annual Power Plant Generation, and Socioeconomic Indicators in the Southeast


## Summary

<This repository contains data and analyses investigating the predictor variables that influence ozone and particulate matter 2.5 concentrations in Southeast region in the United States. Seven states were selected to represent this region: Alabama, Florida, Georgia, Mississippi, North Carolina, South Carolina, and Tennessee. Predictor variables consisted of annual generation of coal-burning power plants (continous), seasonality of Winter and Summer (categorical), and socioeconomic factors such as racial identity, percentage of the population without cars, median income, population, and percentage with housing burden. 

This study aims to assess whether counties with higher ozone and PM 2.5 levels are correlated with this predictor variables. The repository includes data wrangling of TidyCensus, eGRID power plant data, and EPA ozone and PM 2.5 air quality data along with exploratory visualizaitions, and four multi-level models.>

 ## Investigators

<
Lauren Shohan:    
- Affiliation: Duke University Nicholas School of the Environment 
- Contact: lauren.shohan@duke.edu 

Jessalyn Chuang:   
- Affiliation: Duke University Nicholas School of the Environment 
- Contact: jessalyn.chuang@duke.edu 

Weilin Wang:  
- Affiliation: Duke University Nicholas School of the Environment 
- Contact: weilin.wang@duke.edu 
>


## Folder structure, file formats, and naming conventions 

### Folders:
<Datafiles: Contains data used in this project. Contains: eGRID 2022 excel data file, all ozone and PM 2.5 data files for all seven states in the year 2022.>


<Archive: Exploratory files that were not used for final analysis>

### RMD Files:

<PM_Stat_Figures and OZONE_Stat_Figures: These are exploratory files analyzing the PM, Ozone, and EGRID data into exploratory graphs and cleaning the data for analysis.>

<Tidycensus: Contains all data and wrangling for the Tidycensus R package. Pleaser run this one before running the following RMDs.>

<OzonePMCombinedFinal: This contains the cleaned and combined data for PM, Ozone, and eGRID into dataframes for analysis.>

<FinalAnlysis: This data frame reads in the combined csv files of PM and Ozone for both seasons and combines them with our tidycensus dataframe. Exploratory graphs and analysis for all variables is done on this file as well as descriptive statisitics on the variables.>

<multi_lvl_models: Four multi-level models are conducted on this file, two four ozone and two four PM 2.5. QQPlots, standardized residuals/fitted values, and AIC comparisons were conducted to show model comparison. Summary results of all models with p-value and beta values are shown here. >

