# Coursera_Captstone
- Coursera IBM Data Science course capstone project 


INTRODUCTION

In order to tackle climate change we must reduce our use of fossil fuels. One element of the road to net zero emissions is the electrification of transport - powering vehicles with energy generated from renewable energy rather than with petrol or diesel. A question I often get asked as someone working in the energy sector is - [how] will we have enough electricity [for this additional demand]? This question is a complex one, with many variables and elements. The answer lies not only in increasing generation but decreasing demand (through for example efficient appliances) or through shifting demand and balancing it with available energy. 

For this assignment I have chosen to narrow down the question to ‘how much of Manchester’s private electric car charging demand could be met by rooftop solar on supermarkets in the area?’. This is an interesting question because Manchester in the UK is not known for its sunshine. It’s a valuable question because solar panels can be installed on roofs relatively quickly (compared to building wind turbines). And for a densely packed city it’s the main (if not only) solution for local electricity generation. With regards to the supermarket element of the question, even in a lockdown the majority of the population still go to supermarkets, on average on a weekly basis. Supermarkets are usually large flat roofed buildings which present an ideal area for the installation of solar panels. 

The answer to this question (‘how much of Manchester’s private electric car charging demand could be met by rooftop solar on supermarkets in the area?’) can be used by policy makers, community interest groups, Local Authority planners, supermarket owners, charging network operators and others to provide evidence for and create investment around a common goal - net zero emissions.


DATA

Based on the requirements and limitations of what is available the following data will be used in the project:

- Shape files to breakdown Manchester into smaller areas to assist with Foursquare venue search. Source: https://martinjc.github.io/UK-GeoJSON/ (June, 2020)
- Foursquare supermarket venue search (June, 2020)
- Energy generated in a year at the identified supermarkets in Manchester will be derived from the solar potential identified for Manchester in Source: Google Environmental Insights Explorer (June, 2020) https://insights.sustainability.google/places/ChIJ2_UmUkxNekgRqmv-BDgUvtk/download

This estimates the technical solar potential of all buildings in a region. Google Earth imagery is used to analyse roof shape and local weather patterns to create an aggregated solar potential estimate. 

Sunlight: Every included panel receives at least 75 percent of the maximum annual sun in the county. In cases where a building is not in a county, the maximum sun is determined by the max sun received in the city.
Installation size: Each panel is assumed to be 250 Watts with an efficiency of 15.3 percent, a DC to AC derate factor of 85 percent and industry-standard assumptions about other factors. Every included roof has a total potential installation size of at least 2kW and fewer than 1,000kW.

Space & obstacles: Only areas of the roof with enough space to install four adjacent solar panels are included. Only solar arrays on buildings are considered, not other spaces such as parking lots or fields.

The proportion of these buildings that are likely to be supermarkets needs to be estimated in some way in order to get the proportion of the solar potential available in supermarkets. There may be other data sources that are sought and employed as the code is developed and tested.

