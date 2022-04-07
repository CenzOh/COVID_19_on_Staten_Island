# COVID-19 on Staten Island
## Project developed by Vincenzo Mezzio
This project is a continuation of my final project in my Geographic Information Systems class that studied the cause and effects of COVID-19 on Staten Island


## Installation and Setup
For my class, we used the application QGIS version 2.18.28 to develop our maps. This is the version of the software I used to continue the project. To download the software to view the maps in QGIS, you can refer to this link: https://download.osgeo.org/qgis/ Select your operating system and download QGIS OSGeo4W 2.18.28.

After the software downloads, you should have a folder on your desktop named QGIS 2.18 with the shortcut to open the application either through the browser or through the desktop app (QGIS Desktop 2.18.28).

Afterwards, select Project > Open > select the Project File from the appropriately named folder.

## Maps
![Percent_COVID_Cases](/Maps/Map1_5_COVIDCases.jpeg)
**Reference Map 1**, Percent of COVID-19 cases per zip code. This map lists the total percentage of COVID-19 cases from the beginning of the pandemic (February 2020) until May 25th, 2021. Each zip code is denoted a color and the range of COVID-19 cases; zip codes with a dark color represent a higher percentage of COVID-19 cases while the lighter color zip codes represent less percentages of COVID-19 cases. 

![Vaccine_locations](/Maps/Map11_5_VaccineLocationsOffered&Type.jpeg)

**Reference Map 11**, Vaccination Distribution Locations per zip code. This map displays all locations that distribute COVID-19 vaccines as of September 11th, 2021. These locations are broken down by which vaccine is offered (from Pfizer, Moderna, Johnson & Johnson, as well as combination of vaccines offered). The locations are also divided by which require an appointment or are walk ins. The map also displays the number of individuals who received the full vaccine (two doses) per zip code. A zip code with a darker color denotes more individuals have received the vaccine.
Each distribution center is labeled by the street it is located on, which is important for certain distribution centers that have multiple locations on Staten Island (such as CVS Pharmacy). The number of vaccinations received is demonstrated in a choropleth method (graduating color scheme from white to blue, blue indicating more residents have received the vaccination). 

![People_per_square_mile](/Maps/Map13_PeoplePerSquareMile.jpeg)
**Reference Map 13**, People per Square Mile per zip code. The map presents an average count of how many residents are within one square mile in each zip code of Staten Island. This is important to visualize the proximity of residents. The study will go in depth on how individuals being closer to one another have a higher likelihood of spreading the COVID-19 virus.

![Percent_Seniors_Over_65](/Maps/Map15_SeniorsOver65.jpeg)
**Reference Map 15**, Percent of Seniors over 65 per zip code. The map visualizes the percentage of seniors, calculated by dividing the total population with the number of seniors in each zip code of Staten Island. Seniors are classified as being above the age of 65 and in this study, are identified as vulnerable; it is important to map this data.

![Rooms_per_Home](/Maps/Map16_RoomsPerHome.jpeg)
**Reference Map 16**, Average Number of Rooms per Home per zip code. This map lists the average number of rooms out of all homes in each zip code in Staten Island. The average was calculated by dividing the total number of rooms with the number of homes per zip code. The values for every variable in every zip code are represented in Table 1. 

**Table 1 - Important Data Points**
Zip Code | Population | COVID-19 Cases | Percent of COVID-19 Cases | Percent of Seniors | People / Square Mile | Number of Vaccine Centers | Rooms / Home 
--- | --- | --- | --- | --- | --- | --- | --- | 
10314 | 92523 | 11171 | 8.28% | 12.73% | 6650.27 | 9 | 5.8
10312	| 61052	| 7753	| 7.87%	| 9.43%	| 7013.96	| 3	| 6.3
10310	| 23441	| 2812	| 8.34%	| 10.83%	| 12829.03	| 1	| 5.4
10309	| 32939	| 4611	| 7.14%	| 7.74%	| 3862.03	| 3	| 6.2
10308	| 29820	| 3749	| 7.95%	| 11.72%	| 14230.06	| 2	| 6
10307	| 14912	| 2025	| 7.36%	| 8.64%	| 7091.02	| 2	| 6
10306	| 52806	| 7554	| 6.99%	| 15.06%	| 7104.18	| 4	| 5.5
10305	| 42856	| 5631	| 7.61%	| 13.22%	| 8962.46	| 3| 	5.1
10304	| 41886	| 5574	| 7.51%	| 11.53%	| 10617.85	| 1	| 4.9
10303	| 26512	| 3235	| 8.19%	| 7.5%	| 5426	| 3	| 4.9
10302	| 18484	| 2430	| 7.60%	| 11.48%| 	13875.4	| 4	| 5.2
10301	| 38904	| 4547	| 8.55%	| 12.26%	| 10327.23	| 6	| 4.3


## Quick note 
**Reference Map 10**, COVID-19 Cases and Ethnicities was removed due to the lack of connection with this data and other data within the research. 
