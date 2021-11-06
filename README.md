# Visualizing Carbon Dioxide Levels Project
### About: 

For this project, I implemented data analysis using R. I used the libraries readr, dplyr and ggplot2 which helped me to build the project. I analyze two datasets to gain a better understanding and insight about the carbon dioxide levels in the atmosphere. I specifically observed the increase in carbon dioxide levels over the past hundred years relative to the variability in levels of CO2 in the atmosphere over eight millennia.

These data are calculated by analyzing ice cores. Over time, gas gets trapped in the ice of Antarctica. Scientists can take samples of that ice and see how much carbon is in it.

 
### Note:

The first dataset comes from World Data Center for Paleoclimatology, Boulder and NOAA Paleoclimatology Program and describes the carbon dioxide levels back thousands of years “Before Present” (BP) or before January 1, 1950.

The second dataset explores carbon dioxide starting at year zero up until the recent year of 2014. This dataset was compiled by the Institute for Atmospheric and Climate Science (IAC) at Eidgenössische Technische Hochschule in Zürich, Switzerland.

In order to understand the information in these datasets, it’s important to understand two key facts about the data:

- The metric for carbon dioxide level is measured as parts per million or CO2 ppmv. This number describes the number of carbon dioxide molecules per one million gas molecules in our atmosphere.
- The second metric describes years before present, which is “a time scale used mainly in … scientific disciplines to specify when events occurred in the past… standard practice is to use 1 January 1950 as the commencement date of the age scale, reflecting the origin of practical radiocarbon dating in the 1950s. The abbreviation “BP” has alternatively been interpreted as “Before Physics” that is, before nuclear weapons testing artificially altered the proportion of the carbon isotopes in the atmosphere, making dating after that time likely to be unreliable.” This means that saying “the year 20 BP” would be the equivalent of saying “The year 1930.”

### Results: 

First, I removed the scientific notation for better readability. Afterwards, I viewed the data and created NOAA visualization.

<img width="908" alt="Screen Shot 2021-11-06 at 5 08 30 PM" src="https://user-images.githubusercontent.com/89553126/140625146-d53aa108-6370-4a79-8358-7bbc512bdc9a.png">
 
 **NOAA Plot**
 
<img width="692" alt="Screen Shot 2021-11-06 at 5 01 20 PM" src="https://user-images.githubusercontent.com/89553126/140625047-bfa10708-64f5-45a2-ad74-c78eb51db21e.png">
 
Similarily, I did the same for the IAC data. However, I also obtained the CO2_ppmv max in the NOAA data set and set it equal to the variable millenia max which I used for the IAC plot.

<img width="979" alt="Screen Shot 2021-11-06 at 5 10 59 PM" src="https://user-images.githubusercontent.com/89553126/140625191-766e0417-5436-4399-8dfd-7b2d4c1dd720.png">
 
**IAC Plot** 

<img width="692" alt="Screen Shot 2021-11-06 at 5 05 31 PM" src="https://user-images.githubusercontent.com/89553126/140625093-d3832106-3c62-46e3-9dbf-7d83b29cf1bd.png">

In conclusion, I observed an increase trend of CO2 levels over the the millenia. This could lead to a driving ongoing warming of the global climate.
