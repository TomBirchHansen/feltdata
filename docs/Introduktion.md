# Introduction
This API documentation is used in danish regions 


## Overview
The following figure, shows the relationships between the different elements:
 ![overblik.png](https://stoplight.io/api/v1/projects/cHJqOjQ3OTc0/images/yQqe0A07hVg)

## SampleSite vs GeoGIS points/intakes
In relation to GeoGIS a SampleSite (sampleSiteId) is either a point (points-table) or intake (intakes-table). 

The SampleSite GET represents data from both GeoGIS point-table and GeoGIS intake-table as both can be regarded as a samplesite (in relation to the StanLab api specification https://stanlab-api.miljoeportal.dk/openapi/)
The response is structured so it is easy to see if data is an intake or point in GeoGIS.

The SampleSite GET endpoint can be found here: https://feltdata.stoplight.io/docs/feltdata/reference/geogis_openapi.v1.yaml/paths/~1sample/get

## codelist data
codelist fields have a trailing "C" in it's name. It's corisponding codelist-value-field has a trailing "T".
For example:
 - parameterT
 - parameterC






