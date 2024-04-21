# EV Chargers and Sales in California
## Kerina Patel and Dana Morgan

### Introduction
For our final project, we wanted to explore electric vehicle (EV) adoption in California. We wanted to understand which regions in California were hotspots for EV adoption, and wondered whether areas with more EV charging infrastructure would have higher rates of EV adoption. 

### Data Sources
Data on the EV chargers and sales came from the California Energy Commission. The data on EV chargers was accessed via API and included information on the location and type of charger. Data on EV sales was available as a csv file download and included the number of each make and model of all zero emission vehicles (which included hydrogen, electric, and hybrid powered vehicles) sold from 1998 to 2023 on both a county and zip code level. 

We also used data from CalEnviroScreen to calculate county level populations and zip code level disadvantaged community scores. 

### Methodology


### Exploratory Analysis
We began by conducting exploratory analysis on our datasets to get familiar with the data we were working with. 

We looked at the types of EV chargers most common throughout the state to understand where these chargers were most likely to be located. We saw that hotels made up a large portion of publicly available EV chargers. 
![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_11_0.png)

We also looked at the types of EVs most frequently sold in California in 2023, and saw that Tesla's sales were notably higher than any other car brand. 
![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_7_0.png)

We then calculated the total number of EVs sold in each year that we had data for, 1998 through 2023. In looking at the number of EVs sold in the state of California, we saw a sharp increase in the adoption of EVs in the past decade. This follows based on technological advances, improving affordability of EVs, and policy changes encouraging electrification.
![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_12_0.png)


### Key Findings

This chart plots the number of chargers by the number of EVs for each zip code in California. The plotted regression line and calculated R-value shows that there is a slight positive correlation. Establishing causality is a more challenging topic that future research could address. The Correlation Coefficient (R-value) is 0.3548

![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_17_1.png)
    

This chart plots the number of chargers by the average CalEnviroScreen score for each zip code in California. The plotted regression line and calculated R-value shows that there is a slight negative correlation. Establishing causality is a more challenging topic that future research could address. The Correlation Coefficient (R-value) is -0.0233

![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_19_1.png)
  

This first set of maps shows the density of EV sales and EV chargers by county in California. It would appear that Los Angeles County is the hotspot of EV adoption in the state when looking at a basic count of sales and chargers in the county. 
![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_28_0.png)

However, we were suspicious that a simple count was not a complete enough representation of EV adoption, as Los Angeles County is the county with the highest population in the state. When we took into account the population of the county, we found that the Bay Area emerged as a hotspot of EV concentration per capita. To calculate this, we took the number of EVs in the county and divided it by the total county population.
    
![png](255_Final_Code_Compiled_42024_files/255_Final_Code_Compiled_42024_29_0.png)
    
### Sources
California Energy Commission (2024). California Energy Commission Zero Emission Vehicle and Infrastructure Statistics. Data last updated December 31, 2023. Retrieved April 3, 2024 from http://www.energy.ca.gov/zevstats.
