# Exploration of Relationship between Proximity to Expressway and HDB Resale Prices in Singapore
<br>
Some home sellers believe that the value of their HDB flats suffer because they are near expressways, which are very noisy. Others say that proximity to expressway is good, due to convenience and unblocked view (at least for higher floors). This project seeks to explore whether proximity of the HDB to the expressway has a relationship with HDB resale prices.
<br>

## Data Sources
The following public data sources are used for this project:
<br>1. HDB Resale Prices (Jan 2017 to Nov 2022) -  <https://data.gov.sg/dataset/resale-flat-prices?resource_id=f1765b54-a209-4718-8d38-a39237f502b3>
<br>2. National Map Line (for expressway location info) - <https://data.gov.sg/dataset/national-map-line>
<br>3. OneMap API (for HDB location info) - <https://www.onemap.gov.sg/docs/>

## File Description
This project includes one Jupyter notebook, the notebook file rendered into html document and the data files.

## Results
Hypothesis testing on difference in means show that the mean resale prices for HDBs near expressway is significantly lower than that of HDBs not near expressway, for 2-room, 3-room, 4-room, 5-room and executive HDBs. From descriptive statistics, mean resale prices were approximately $6k, $8k, 11k, $15k and $61k lower for 2-room, 3-room, 4-room, 5-room and executive HDBs respectively.

## Limitations
This project recognises that HDB prices are affected by many different factors and comparing resale prices only by its proximity to expressway could undermine the effects of other factors, e.g., size of HDB and remaining lease period. Future iterations of the project will explore the effect of other factors that could affect HDB resale prices and generate predictions for the prices. 

## References and Acknowledgements
[1] [Geocoding Singapore Coordinates: OneMap API](https://towardsdatascience.com/geocoding-singapore-coordinates-onemap-api-3e1542bf26f7)
[2] [Z Test Statistics Formula & Python Implementation](https://towardsdatascience.com/z-test-statistics-formula-python-implementation-3755d67ba0e7)
