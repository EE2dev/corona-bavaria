# corona-bavaria
Data about the spread of the corona virus in Bavaria

## Data

The data file corona_bavaria.json has been manually created and collected from various sources since no official table with historic data on that level was found.
It is created with much rigor, however, several properties should be known:
- different sources report the infected cases on different days (different publication frequency), making it hard to correctly assign dates to cases
- no source was found to consistently report on people becoming healthy after being infected. As a result, the total number of infected people are counted from day 1. It does not represent the number of infected people on a particular day



#### Sources:
- https://de.wikipedia.org/wiki/COVID-19-F%C3%A4lle_in_Deutschland
- https://www.br.de/nachrichten/deutschland-welt/liveticker-aktuelle-informationen-zum-coronavirus,RoxMtok
- https://www.stmgp.bayern.de/presse/bayerisches-gesundheitsministerium-sechs-weitere-coronavirus-faelle-in-bayern-bestaetigt/?output=pdf
- http://opendatalab.de/projects/geojson-utilities/


## Tools

A collection of tools which might be helpful to process the data:

- [converting JSON to CSV](http://convertcsv.com/json-to-csv.htm)
- [export of regions of Germany in geoJSON format plus additional data](http://opendatalab.de/projects/geojson-utilities/)
- [converting GeoJSON to TopoJSON (1)](http://shancarter.github.io/distillery/)
- [converting GeoJSON to TopoJSON (2)](http://jeffpaine.github.io/geojson-topojson/)