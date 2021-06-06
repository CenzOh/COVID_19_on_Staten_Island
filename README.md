# COVID-19 on Staten Island
## Project developed by Vincenzo Mezzio
This project is a continuation of my final project in my Geographic Information Systems class that studied the cause and effects of COVID-19 on Staten Island


## Installation and Setup
For my class, we used the application QGIS version 2.18.28 to develop our maps. This is the version of the software I used to continue the project. To download the software to view the maps in QGIS, you can refer to this link: https://download.osgeo.org/qgis/ Select your operating system and download QGIS OSGeo4W 2.18.28.

After the software downloads, you should have a folder on your desktop named QGIS 2.18 with the shortcut to open the application either through the browser or through the desktop app (QGIS Desktop 2.18.28).

Afterwards, select Project > Open > select the Project File from the appropriately named folder.

## Maps
![VaccineLocations](/Maps/Map9_VaccineLocations.jpeg)

This map demonstrates the locations of all vaccination distribution centers on Staten Island. Each distribution center is labeled by the street it is located on, which is important for certain distribution centers that have multiple locations on Staten Island (such as CVS Pharmacy). I also characterized each location by residents being able to walk in for the vaccine or by scheduling an appointment for the vaccine. I found it would be important to see if residents would be more willing to receive the vaccine if they could simply walk in to receive the vaccine. Interestingly, I have found that not many distribution centers offer the vaccine as a walk in. I have concluded that walk-in vaccination centers are not a large factor in residents willing to receive the vaccines; rather, an area with more vaccines would most likely have more residents receive the vaccinations. The number of vaccinations received is demonstrated in a choropleth method (graduating color scheme from white to blue, blue indicating more residents have received the vaccination). The zip code 10314 has 9 vaccination distribution centers (one of them offers walk in vaccination) and this zip code has the most vaccinations (at least 33,000 first dose vaccinations as of May 17th, 2021. Other zip codes such as 10310, 10307, and 10302 which have 1, 2, and 3 vaccination centers respectively have the lowest number of vaccinations (approximately 5,000 to 10,000 vaccinations). The more vaccination centers that are present, the more likely Staten Island residents would receive the vaccination.

![VaccineLocations](/Maps/Map10_CovidCaseEthnicity.jpeg)

This map demonstrates the ratio of ethnicities per zip code on Staten Island in the form of a pie chart. I have also included the number of COVID-19 cases. I was initially developing a map based on the number of COVID-19 cases by ethnicity, however, I was unable to find any data about this. I was able to discover data regarding the number of residents per zip code on Staten Island based on their ethnicity. I opted to include ethnicity data on White, Black, Asian, and Hispanic because they were the highest values compared to data on other ethnicities. I discovered that a great deal of White residents lives on the South Shore (Hispanic numbers are the second highest out of White, Black, and Asian) including zip codes 10307, 10309, and 10312. Also, a great deal of Hispanic residents lived on the North Shore (Black numbers are generally the second highest our of White, Asian, and Hispanic) including zip codes 10303, 10302, and 10310.
I was unable to reach a conclusion regarding ethnicity playing a role in COVID-19 cases. In a zip code such as 10314, it holds the highest total population of residents (over 85,000 residents) and thus has the highest number of COVID-19 cases. Both zip codes 10308 and 10304 have a drastic difference in number of population (10308 has 27,000 residents while 10304 has 41,000 residents). The number of White residents in 10308 is 25,000 while 10304 is 14,000 (10308 is higher), the Black resident population in 10308 is 40 while in 10304 it is 10,000 (10304 is higher), the Asian population number is 1,000 in 10308 and 4,000 in 10304 (10304 is higher), and the Hispanic population is 3,000 in 10308 and 11,000 in 10304 (10304 is higher). Overall, 10304 has a higher population for Black, Asian, and Hispanic residents, however, they are both in the same margin in the number of COVID-19 cases being between 3,400 and 4,900. The difference in ethnicity does not change the number of COVID-19 cases. I believe the overall population makes a difference between which zip codes had more COVID-19 cases and which zip codes had less COVID-19 cases (I have shown this in a previous map).


![VaccineLocations](/Maps/Map11_VaccineLocationsType.jpeg)

