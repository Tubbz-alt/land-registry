# Land Registry

regions is list from https://www.gov.uk/government/collections/download-inspire-index-polygons

format of zip download url is http://data.inspire.landregistry.gov.uk/{REGION_NAME}.zip

where REGION_NAME has is region_name from regions.csv with spaces replaced with underscores


TODO:

- import into PostGIS by converting gml to [ST_GeomFromGML](https://postgis.net/docs/ST_GeomFromGML.html)
- run queries to check which polygon address is in
- get links to local authority URLs for each region
