# Houston Open Data Sources

Open data about Houston and Harris County is scattered across many portals that nobody tracks together.
This registry lists every source we know of: **7,218 datasets and layers across 16 sources**,
of which **150** are loaded into the explorer at https://fasthouston.org.

Browse and search it at
https://fasthouston.org/catalog. To add a source, suggest it there.

| Source | Publisher | Items | Loaded | Notes |
|---|---|---:|---:|---|
| [Harris County ArcGIS Online](https://services.arcgis.com/su8ic9KbA7PYVxPS/arcgis/rest/services) | Harris County (departments and precincts) | 3,112 | 16 | One organization shared by county departments, precincts and staff. Mixes authoritative layers (fire stations, parks, crashes) with many working copies and one-off maps; review before use. |
| [Rice University ArcGIS Online](https://services.arcgis.com/lqRTrQp2HrfnJt8U/arcgis/rest/services) | Rice University (GIS/Data Center, Kinder Institute, courses) | 2,888 | 0 | Research and class projects. Houston gems (HCFCD buyout lots, draft 2026 FEMA flood map, historical census, redlining) among worldwide student work. Research copies of agency data need permission before reuse. |
| [Houston Advanced Research Center (HARC) ArcGIS Online](https://services2.arcgis.com/LYMgRMwHfrWWEg3s/arcgis/rest/services) | HARC | 528 | 1 | Environmental and regional research layers; source of the 2021 city cool-center list. |
| [City of Houston GIS (ArcGIS Hubs)](https://geohub.houstontx.gov) | City of Houston | 314 | 119 | Two Hub sites (Public Works geohub, citywide mycity) over several ArcGIS servers. Official. |
| [Harris County Flood Control District ArcGIS Online](https://services2.arcgis.com/nLl0k0Mja5hnSeSl/arcgis/rest/services) | Harris County Flood Control District | 265 | 4 | High-water marks, floodplains, projects, acreage by program. Source of the storm HWM layers. |
| [City of Houston Open Data (data.houstontx.gov)](https://data.houstontx.gov) | City of Houston | 94 | 0 | Separate from the GIS hubs. Mostly spreadsheets; finance (checkbook, payroll, budget) and census stay current, much else frozen since a 2023 migration. |
| [U.S. Census Bureau](https://api.census.gov) | U.S. Census Bureau | 4 | 3 |  |
| [FEMA (OpenFEMA and National Flood Hazard Layer)](https://www.fema.gov/about/openfema/data-sets) | Federal Emergency Management Agency | 4 | 3 |  |
| [Centers for Disease Control and Prevention](https://data.cdc.gov) | CDC / ATSDR | 2 | 2 |  |
| [U.S. Geological Survey water data](https://waterservices.usgs.gov/nwis/) | USGS | 1 | 0 |  |
| [Stanford Open Policing Project](https://openpolicing.stanford.edu/data/) | Stanford University | 1 | 0 |  |
| [TxDOT Crash Records Information System (CRIS)](https://cris.dot.state.tx.us/) | Texas Department of Transportation | 1 | 0 |  |
| [City of Houston 311 public data extracts](https://www.houstontx.gov/311/) | City of Houston 311 | 1 | 1 |  |
| [METRO (Harris County transit)](https://www.ridemetro.org/about/metro-data) | Metropolitan Transit Authority of Harris County | 1 | 0 |  |
| [U.S. Environmental Protection Agency](https://data.epa.gov/efservice/) | EPA | 1 | 1 |  |
| [Texas Commission on Environmental Quality](https://www.tceq.texas.gov/) | TCEQ | 1 | 0 |  |

## Worth adding next

Reviewed and useful; not loaded yet.

- **Budget** (City of Houston Open Data (data.houstontx.gov)): Adopted budget [link](https://data.houstontx.gov/dataset/budget)
- **Checkbook** (City of Houston Open Data (data.houstontx.gov)): Every City payment, monthly CSVs, current [link](https://data.houstontx.gov/dataset/checkbook)
- **City of Houston Residential Building Permits by Month and Year** (City of Houston Open Data (data.houstontx.gov)): Residential permits by month [link](https://data.houstontx.gov/dataset/residential-building-permits)
- **Payroll** (City of Houston Open Data (data.houstontx.gov)): City payroll by department, current [link](https://data.houstontx.gov/dataset/payroll)
- **Hazard mitigation (FEMA-funded buyouts/elevations) properties, ZIP level** (FEMA (OpenFEMA and National Flood Hazard Layer)) [link](https://www.fema.gov/api/open/v4/HazardMitigationAssistanceMitigatedProperties)
- **AirMonitorLast365Days** (Harris County ArcGIS Online): County community air sensors, rolling year of 15-minute readings [link](https://services.arcgis.com/su8ic9KbA7PYVxPS/ArcGIS/rest/services/AirMonitorLast365Days/FeatureServer/0)
- **AirMonitorLast7Days** (Harris County ArcGIS Online): County community air sensors, 15-minute readings, ~1 hour behind [link](https://services.arcgis.com/su8ic9KbA7PYVxPS/ArcGIS/rest/services/AirMonitorLast7Days/FeatureServer/0)
- **CenterPoint Streetlight Data: CNP_SL_CP1Inc** (Harris County ArcGIS Online): CenterPoint streetlights (two sublayers, meaning unclear) [link](https://services.arcgis.com/su8ic9KbA7PYVxPS/ArcGIS/rest/services/CenterPoint_Streetlight_Data/FeatureServer/0)
- **CenterPoint Streetlight Data: CNP_SL_CP1UnInc** (Harris County ArcGIS Online): CenterPoint streetlights (two sublayers, meaning unclear) [link](https://services.arcgis.com/su8ic9KbA7PYVxPS/ArcGIS/rest/services/CenterPoint_Streetlight_Data/FeatureServer/1)
- **CenterPoint Streetlight Data: COH_Neighborhoods_CP1** (Harris County ArcGIS Online): CenterPoint streetlights (two sublayers, meaning unclear) [link](https://services.arcgis.com/su8ic9KbA7PYVxPS/ArcGIS/rest/services/CenterPoint_Streetlight_Data/FeatureServer/2)
- **HCFCD buyout areas (official)** (Harris County Flood Control District ArcGIS Online): Official HCFCD buyout areas (80) with priority rankings, % publicly owned, structures remaining [link](https://services2.arcgis.com/nLl0k0Mja5hnSeSl/ArcGIS/rest/services/HCFCD_Buyout_Areas/FeatureServer/0)
- **GTFS schedules (service frequency by stop and route)** (METRO (Harris County transit)) [link](https://www.ridemetro.org/about/metro-data)
- **Draft 2026 FEMA flood map, Harris County (MAAPnext)** (Rice University ArcGIS Online): Draft 2026 FEMA flood map for Harris County (HCFCD MAAPnext modeling) [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/RasterFull_MAAPNext_Flood/FeatureServer/0)
- **HCFCD acquired buyout lots (FEMA lots and other buyouts)** (Rice University ArcGIS Online): HCFCD buyout lots (4,554; 2,999 FEMA-funded), received by Rice from HCFCD Mar 2026 [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/ACQUIRED_BOL/FeatureServer/0)
- **HOLC Houston Redlining polygon** (Rice University ArcGIS Online): 1930s HOLC redlining map of Houston [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/HOLC_Houston_Redlining_polygon/FeatureServer/0)
- **Houston traffic stops (race, reason, outcome) (Data Jam, Jun 2017)** (Stanford Open Policing Project) [link](https://openpolicing.stanford.edu/data/)
- **Air emission event reports (facility self-reported releases)** (Texas Commission on Environmental Quality) [link](https://www2.tceq.texas.gov/oce/eer/)
- **Statewide crash extract 2019-2024 (free account required)** (TxDOT Crash Records Information System (CRIS)) [link](https://cris.dot.state.tx.us/)
- **ACS 5-year estimates by block group** (U.S. Census Bureau) [link](https://api.census.gov/data/2024/acs/acs5)
- **Lake Houston water quality and discharge, 8 stations, every 15 minutes (Data Jam, Jun 2018)** (U.S. Geological Survey water data) [link](https://waterservices.usgs.gov/nwis/iv/)

## Needs permission first

Publicly readable, but research or working copies of agency data: ask before using.

- **alldatamerged HFD Only SpatialJoin ExportFeatures** (Rice University ArcGIS Online): Research copy of HFD incidents; ask Rice/HFD before use [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/alldatamerged_HFD_Only_SpatialJoin_ExportFeatures/FeatureServer/0)
- **HFD incidents 2019-2025 (research copy)** (Rice University ArcGIS Online): Research copy of 2.46M HFD incidents; ask Rice/HFD before use [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/HFD_FinalSituation_XYTableToPoint/FeatureServer/0)
- **HFD incidents 2019-2025 (research copy)** (Rice University ArcGIS Online): Research copy of 2.46M HFD incidents; ask Rice/HFD before use [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/HFD_FinalSituation_XYTableToPoint/FeatureServer/3)
- **HFD incidents 2019-2025 (research copy)** (Rice University ArcGIS Online): Research copy of 2.46M HFD incidents; ask Rice/HFD before use [link](https://services.arcgis.com/lqRTrQp2HrfnJt8U/ArcGIS/rest/services/HFD_FinalSituation_XYTableToPoint/FeatureServer/4)

## Status meanings

- **loaded**: in the warehouse and queryable by the explorer's AI analyst.
- **candidate**: reviewed and worth loading.
- **permission_needed**: usable-looking, but ask the owner first.
- **not_loaded**: everything else. ArcGIS organizations mix authoritative layers with many staff working copies; names that look like working copies are flagged and hidden by default on the catalog page.
