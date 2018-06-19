# Reporting on the Dakota Access Pipeline protests of 2016.
## An analysis and visualization of federal data on crude oil spills  

The following workshop walks you through a data analysis and visualization I carried out for [Undark magazine](https://undark.org/article/oil-pipeline-safety-dakota-access-standing-rock/) on the risk of an oil spill surrounding the Dakota Access Pipeline debate. It is an introduction to finding, cleaning and visualizing federal data using Excel and Carto.com. 

### Questions I had that guided my reporting

![alt text](http://aleszu.com/workshops/oilwater1.png)

### What are some of things these protestors are so angry about?

![alt text](http://aleszu.com/workshops/oilwater4b.jpg)

### How often do spills occur? And when pipelines rupture, how much oil spills?

![alt text](http://aleszu.com/workshops/oilwater4.png)

### Where in the U.S. do these spills occur?

![alt text](http://aleszu.com/workshops/oilwater2.png)

### Could we map that?

![alt text](http://aleszu.com/workshops/oilwater4d.jpg)

# How I put it together

### I found [data](https://www.phmsa.dot.gov/pipeline/library/data-stats/flagged-data-files) from the Pipeline and Hazardous Materials Safety Administration (PHMSA). 

![alt text](http://aleszu.com/workshops/oilwater5.png)

### I downloaded a zip file. 

![alt text](http://aleszu.com/workshops/oilwater6.png)

### The government was nice enough to tell me what every column corresponded to.

![alt text](http://aleszu.com/workshops/oilwater7.png)

### All I really had to do in Excel was filter, sort and count. 

![alt text](http://aleszu.com/workshops/oilwater8.png)

### I dropped my cleaned up spreadsheet into Carto.com

![alt text](http://aleszu.com/workshops/carto-oilwater.png)

### And it blew up on [Twitter](https://twitter.com/badhombrenps/status/824643921397555201)!

![alt text](http://aleszu.com/workshops/twitter-oilwater.png)

# Do it yourself

For this workshop, let's start with a filtered version of hazardous spills since 2010. If you want the full zip file of PHMSA flagged incidents go [here](https://www.phmsa.dot.gov/pipeline/library/data-stats/flagged-data-files).

## Let's start with Datawrapper.de

Go to [datawrapper.de](http://datawrapper.de) and click Create a Map. Then, click Symbol maps.

![alt text](http://aleszu.com/workshops/datawrapper-oilwater.png)

Try asking yourself another question and answer it with this dataset. Try asking questions on: 
1. A commodity besides crude oil 
2. The riskiest pipeline operators 
3. Spills in specific states

## Build the map yourself

1. Boot up [Carto.com](http://Carto.com), create a login and upload the CSV from above. 

2. Plot the data by latitude and longitude and then style the points by net barrels recovered. 

3. To add interactivity to your map, play with the "widgets" function. Add a "histogram" pulled from one of your columns, like "net_loss_barrels," and a "category" from the "iyear" column.

4. What other geographic information might be helpful? Let's add in the shapefiles for the U.S.'s crude oil pipelines. Those can be found in a [zip](https://www.eia.gov/maps/map_data/CrudeOil_Pipelines_US_EIA.zip) from the [U.S. Energy Information Administration](https://www.eia.gov/maps/layer_info-m.php). 

5. Extra points if you can track down and plot the shapefile for the Standing Rock reservation.

Read the full story on Undark [here](https://undark.org/article/oil-pipeline-safety-dakota-access-standing-rock/).

![alt text](http://aleszu.com/workshops/carto-oilwater.png)

Link to Undark interactive map [here](https://undark.carto.com/viz/e053d3f2-b66b-11e6-a2ce-0e233c30368f/public_map) and workshop interactive map [here](https://storybench.carto.com/builder/eaeb6a08-0e47-11e7-a547-0ef24382571b/).

## Mapping nuclear data 

Try mapping nuclear powerplants. Data from [CarbonBrief](https://www.carbonbrief.org/mapped-the-worlds-nuclear-power-plants).

## European data 

[Shapefiles](https://www.data.gouv.fr/fr/datasets/delimitation-parcellaire-des-aoc-viticoles-de-linao/) of France's AOC regions. 

A great list from UPenn on European [GIS data](https://guides.library.upenn.edu/c.php?g=475518&p=3254771).

A shapefile of European natural gas pipelines [here](https://enipedia.org/wiki/NaturalGasInfrastructure).


