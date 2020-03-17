# corona-bavaria
Data about the spread of the corona virus in Bavaria

## 1. Data

The data file corona_bavaria.json has been manually created and collected from various sources since no official table with historic data on that level was found.
It is created with much rigor, however, several properties should be known:
- different sources report the infected cases on different days (different publication frequency), making it hard to correctly assign dates to cases
- no source was found to consistently report on people becoming healthy after being infected. As a result, the total number of infected people are counted from day 1. It does not represent the number of infected people on a particular day
- this dataset is updated regularly (augmented by new cases)

#### 1.1 Data description:

#### 1.2 Sources:
- https://www.stmgp.bayern.de/
- https://www.lgl.bayern.de/gesundheit/infektionsschutz/infektionskrankheiten_a_z/coronavirus/karte_coronavirus/index.htm
- https://de.wikipedia.org/wiki/COVID-19-F%C3%A4lle_in_Deutschland
- https://www.br.de/nachrichten/deutschland-welt/liveticker-aktuelle-informationen-zum-coronavirus,RoxMtok
- http://opendatalab.de/projects/geojson-utilities/
- https://de.wikipedia.org/wiki/Liste_der_Landkreise_und_kreisfreien_St%C3%A4dte_in_Bayern


## 2. Tools

A collection of tools which might be helpful to process the data:

- [converting JSON to CSV](http://convertcsv.com/json-to-csv.htm)
- [export of regions of Germany in geoJSON format plus additional data](http://opendatalab.de/projects/geojson-utilities/)
- [converting GeoJSON to TopoJSON (1)](http://shancarter.github.io/distillery/)
- [converting GeoJSON to TopoJSON (2)](http://jeffpaine.github.io/geojson-topojson/)