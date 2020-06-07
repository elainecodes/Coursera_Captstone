# Coursera_Captstone
- Coursera IBM Data Science course capstone project 


INTRODUCTION

Scientists agree that climate change is being caused by the emission of greenhouse gases, like carbon dioxide, from the burning of fossil fuels. In order to tackle climate change we must reduce our carbon emissions. One way we can do this is by powering vehicles with electricity generated from renewable energy rather than with fossil fuels (petrol or diesel). 

For this assignment I have chosen to answer the question ‘how much of Manchester’s private electric car charging demand could be met by rooftop solar on supermarkets in the area?’. This is an interesting question because Manchester in the UK is not known for its sunshine. It’s a valuable question because solar panels can be installed on roofs relatively quickly (compared to building wind turbines). And for a densely packed city it’s the main (if not only) solution for local electricity generation. With regards to the supermarket element of the question, even in a lockdown the majority of the population still go to supermarkets, on average on a weekly basis. Supermarkets are usually large flat roofed buildings which present an ideal area for the installation of solar panels. 

The answer to this question (‘how much of Manchester’s private electric car charging demand could be met by rooftop solar on supermarkets in the area?’) can be used by:
- policy makers and or Local Authorities to set targets and incentives for the installation of solar panels on supermarkets and installation of electric vehicle charging points in supermarket car parks, 
- community interest groups - to campaign for the rollout of local charging points and solar panel installations, 
- supermarket owners, solar panel installers, charging network operators and others to establish the business case and seek investment or funding for the rollout of electric vehicle charging points and solar panels.


DATA

The following data will be used in the project:

- CSV of Manchester districts and wards by latitude and longitude, Source: https://www.doogal.co.uk/UKPostcodes.php?Search=M (June, 2020) 
- Foursquare supermarket venue search (June, 2020)
- The solar potential identified for Manchester in Source: Google Environmental Insights Explorer (June, 2020) https://insights.sustainability.google/places/ChIJ2_UmUkxNekgRqmv-BDgUvtk/download

Google Environmental Insights Explorer shows solar potential data in MWh/year and grouped by roof type (flat or North, East, South or West facing). It says for example that 271 flat roofs provide 195,000 MWh/year solar potential so we will use this as a proxy to calculate solar potential of supermarket roofs. (We will have to make some assumptions which will be clearly stated in the report). Other data sources may also be sought and employed as the code is developed and tested. 

