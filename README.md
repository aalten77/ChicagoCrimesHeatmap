# ChicagoCrimesHeatmap

Hotspot analysis project for GEOG 171 - Advanced GIS @ SJSU. Spring 2019.

### GIS Data Dictionary
To read the data dictionary, follow this link: [altena_g171_gisdatadic_final.pdf](https://drive.google.com/file/d/1Ek2wBgIFi117gup8pfb5vMOmfUxJIwsg/view?usp=sharing)

## Spatial Analysis: 
View the following notebook for methodology used to cluster the data.
[DBSCAN_Downtown19.ipynb](https://github.com/aalten77/ChicagoCrimesHeatmap/blob/master/DBSCAN_Downtown19.ipynb)

### Data: 
View the following CSVs for the Chicaco Crime dataset from Google BigQuery.
* [CrimeDowntown2018_jan_apr.csv](https://github.com/aalten77/ChicagoCrimesHeatmap/blob/master/CrimeDowntown2018_jan_apr.csv)
* [CrimeDowntown2018_may_aug.csv](https://github.com/aalten77/ChicagoCrimesHeatmap/blob/master/CrimeDowntown2018_may_aug.csv)
* [CrimeDowntown2018_sept_dec.csv](https://github.com/aalten77/ChicagoCrimesHeatmap/blob/master/CrimeDowntown2018_sept_dec.csv)

## Heatmap Visualization:
For Mapbox implementation of the timelapse, view the HTML file. 
[index.html](https://github.com/aalten77/ChicagoCrimesHeatmap/blob/master/index.html)

You can render the visualization here: [https://aalten77.github.io/ChicagoCrimesHeatmap/](https://aalten77.github.io/ChicagoCrimesHeatmap/)

## Results of clustered points: 
Find the resulting Geojson below from this file: 
[crimes-dbscan_2018_v2.geojson](https://github.com/aalten77/ChicagoCrimesHeatmap/blob/master/crimes-dbscan_2018_v2.geojson). A Mapbox web map will render the points for viewing. 
