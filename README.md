# Bible Geocoding KML in Vietnamese

## Introduction

This project seeks to provide a KML file with Vietnamese translations of all the place names in the Bible for use in Google Maps, QGIS, and other mapping software. 

This file is based on https://a.openbible.info/geo/kmls/all-most-likely.kmz. The source for this data is available at https://github.com/openbibleinfo/Bible-Geocoding-Data.

## License

As with the source data, this data is licensed under a Creative Commons Attribution 4.0 license.

OpenStreetMap data is licensed under ODbL 1.0, which is similar to CC-BY-SA.
 
## List of Contributors

Daniel Owens

Bui Duc Huynh

## Validation

The schema is in ./kml-schema/kml21.xsd. To validate, use the following command: 

xmllint --noout --schema ./kml-schema/kml21.xsd Bible-Geocoding-all-most-likely-vi.kml