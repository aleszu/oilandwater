# Oil and Water data analysis for Undark

The following workshop walks you through a data analysis and visualization I carried out for [Undark magazine](https://undark.org/article/oil-pipeline-safety-dakota-access-standing-rock/) on the risk of an oil spill surrounding the Dakota Access Pipeline debate. It is an introduction to finding, cleaning and visualizing federal data using Excel and Carto.com. 

## The Dakota Access Pipeline protest of 2016

### Questions I had that guided my reporting

![alt text](http://aleszu.com/workshops/oilwater1.png)

### What are these protestors angry about?

![alt text](http://aleszu.com/workshops/oilwater2.png)

### Could DAPL rupture? If so, what was the risk?

![alt text](http://aleszu.com/workshops/oilwater4.png)

### How often do spills occur?

### When they rupture, how much oil spills?

### And where in the U.S. do these spills occur?

## How I put it together

I found [data](https://www.phmsa.dot.gov/pipeline/library/data-stats/flagged-data-files) from the Pipeline and Hazardous Materials Safety Administration (PHMSA).

![alt text](http://aleszu.com/workshops/oilwater5.png)

I downloaded a zip file.

![alt text](http://aleszu.com/workshops/oilwater6.png)

The government was nice enough to tell me what every column corresponded to.

![alt text](http://aleszu.com/workshops/oilwater7.png)

![alt text](http://aleszu.com/workshops/oilwater8.png)

## Do the analysis yourself

For this workshop, download a filtered version I cleaned up that only has crude oil spills over 100 barrels (net lost) since 2010 [here](https://drive.google.com/file/d/0B56vzj8m6JInRWZGM0tyQk94VTA/view?usp=sharing). If you want the full zip file of PHMSA flagged incidents go [here](https://www.phmsa.dot.gov/pipeline/library/data-stats/flagged-data-files).

## Build the map yourself

Boot up [Carto.com](http://Carto.com), create a login and upload the CSV from above. Plot the data by latitude and longitude and then style the points by net barrels recovered. Voilá.

You might also want to add in shapefiles for the country's crude oil pipelines. Those can be found in a [zip](https://www.eia.gov/maps/map_data/BorderCrossing_Liquids_EIA.zip) from the [U.S. Energy Information Administration](https://www.eia.gov/maps/layer_info-m.php). Extra points if you can track down and plot the shapefile for the Standing Rock reservation.

Read the full story on Undark [here](https://undark.org/article/oil-pipeline-safety-dakota-access-standing-rock/).



