---
layout: post
title:  "Cambridge OpenData"
date:   2020-03-25
---


#### [Cambridge OpenData Github Pages Landing Page](http://cambridgegis.github.io/gisdata.html)
(includes master list of datasets)

#### [Cambridge OpenData GitHub Repo](https://github.com/cambridgegis/cambridgegis_data)
Examples: 
* [Park Benches GeoJSON](https://github.com/cambridgegis/cambridgegis_data/blob/master/Infra/Park_Benches/INFRA_ParkBenches.geojson)
* [City Employee Salaries](https://data.cambridgema.gov/Budget-Finance/Budget-Salaries/ixg8-tyau/data)

#### [Cambridge OpenData Datasets browser](https://data.cambridgema.gov/browse)
Contains a subset of the data from the github repo, hard to tell exactly what.

Each dataset can be opened and visualized in Socrata. Does not appear to be a way to import data into Socrata.

Supposedly has a plotly integration, but currently broken.

#### [Cambridge GIS CityViewer](https://www.cambridgema.gov/GIS/interactivemaps/Cambridgecityviewer)
Some preloaded datasets, can be visualized in what seems like a custom viewer?

[Direct Launch Link](https://gis.cambridgema.gov/map/Viewer.aspx)


## Bike Totem Visualization from Socrata

iFrame (doesn't seem to work)

<iframe src="https://data.cambridgema.gov/dataset/Bike-Totem-Traffic-by-time-direction/2k9t-c864/embed?width=800&height=600" width="800" height="600" style="border:0; padding: 0; margin: 0;"></iframe>

JS Embed

<script type="text/javascript" charset="UTF-8" data-locale="en" data-socrata-domain="data.cambridgema.gov" src="https://data.cambridgema.gov/component/visualization/v1/socrata-visualizations-loader.js"></script>
<a class="socrata-visualization-embed" data-embed-version="1" data-height="600" data-socrata-domain="data.cambridgema.gov" data-vizcan-uid="2k9t-c864" data-vif="{&quot;configuration&quot;:{&quot;viewSourceDataLink&quot;:true,&quot;showDimensionLabels&quot;:true,&quot;xAxisScalingMode&quot;:&quot;pan&quot;,&quot;showValueLabels&quot;:false,&quot;dimensionLabelAreaSize&quot;:43},&quot;series&quot;:[{&quot;unit&quot;:{&quot;other&quot;:&quot;Intervals&quot;,&quot;one&quot;:&quot;Interval&quot;},&quot;color&quot;:{&quot;secondary&quot;:&quot;#a6cee3&quot;,&quot;highlight&quot;:&quot;#cccccc&quot;,&quot;palette&quot;:&quot;categorical&quot;,&quot;primary&quot;:&quot;#a6cee3&quot;},&quot;showLegend&quot;:true,&quot;type&quot;:&quot;columnChart&quot;,&quot;dataSource&quot;:{&quot;measure&quot;:{&quot;aggregationFunction&quot;:&quot;sum&quot;,&quot;columnName&quot;:&quot;exits&quot;},&quot;orderBy&quot;:{&quot;parameter&quot;:&quot;dimension&quot;,&quot;sort&quot;:&quot;asc&quot;},&quot;type&quot;:&quot;socrata.soql&quot;,&quot;datasetUid&quot;:&quot;q8v9-mcfg&quot;,&quot;dimension&quot;:{&quot;columnName&quot;:&quot;time&quot;,&quot;aggregationFunction&quot;:null},&quot;filters&quot;:[]},&quot;label&quot;:null},{&quot;unit&quot;:{&quot;other&quot;:&quot;Intervals&quot;,&quot;one&quot;:&quot;Interval&quot;},&quot;color&quot;:{&quot;secondary&quot;:&quot;#5b9ec9&quot;,&quot;highlight&quot;:&quot;#cccccc&quot;,&quot;palette&quot;:&quot;categorical&quot;,&quot;primary&quot;:&quot;#5b9ec9&quot;},&quot;showLegend&quot;:true,&quot;type&quot;:&quot;columnChart&quot;,&quot;dataSource&quot;:{&quot;measure&quot;:{&quot;aggregationFunction&quot;:&quot;sum&quot;,&quot;columnName&quot;:&quot;entries&quot;},&quot;orderBy&quot;:{&quot;parameter&quot;:&quot;dimension&quot;,&quot;sort&quot;:&quot;asc&quot;},&quot;type&quot;:&quot;socrata.soql&quot;,&quot;datasetUid&quot;:&quot;q8v9-mcfg&quot;,&quot;dimension&quot;:{&quot;columnName&quot;:&quot;time&quot;,&quot;aggregationFunction&quot;:null},&quot;filters&quot;:[]},&quot;label&quot;:null}],&quot;format&quot;:{&quot;type&quot;:&quot;visualization_interchange_format&quot;,&quot;version&quot;:3},&quot;description&quot;:&quot;&quot;,&quot;id&quot;:&quot;2bea41bb-7dda-4997-9cda-ccba6e606f27&quot;,&quot;title&quot;:&quot;&quot;}" data-width="800" href="https://data.cambridgema.gov/dataset/Eco-Totem-Broadway-Bicycle-Count/q8v9-mcfg?referrer=embed" rel="external" target="_blank">View the data</a>
