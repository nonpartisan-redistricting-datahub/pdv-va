# mggg-va

Replication files and data for [MGGG's VA](https://github.com/mggg-states/VA-shapefiles) shapefile.

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/mggg-virginia-precincts-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.


## Folder contents:

- `VA_MGGG_replication_file.ipynb`
  - processing file for reproducing MGGG’s VA shapefile with the data MGGG described
  
- `VA_MGGG_replication_file-census.ipynb ` (suggested for use)
  - processing file for reproducing MGGG’s VA shapefile using Census demographic data
  
- verification folder
  - folder that contains verification replication file (`VA_verify.ipynb`) and report outputs


## Raw from source: 

### All sources accessed 7/17/2020 and available upon request:
  - congressional_districts
    - [Common Wealth of Virginia Division of Legislative Services](https://redistricting.dls.virginia.gov/PlanList.aspx?type=GIS)
  - demographic_data  
    - [IPUMS NHGIS](https://www.nhgis.org/)
  - house_districts2011
    - [Common Wealth of Virginia Division of Legislative Services](https://redistricting.dls.virginia.gov/PlanList.aspx?type=GIS)
  - house_districts2019
    - [Common Wealth of Virginia Division of Legislative Services](https://redistricting.dls.virginia.gov/PlanList.aspx?type=GIS)
  - PGP-election-precincts
    - Princeton Gerrymandering Project's VA-gerrymander [repo](https://github.com/PrincetonUniversity/VA-gerrymander)
  - senate_districts
    - [Common Wealth of Virginia Division of Legislative Services](https://redistricting.dls.virginia.gov/PlanList.aspx?type=GIS)
  - VA_blk-level_shapefile
    - 2010 Virginia block-level shapefile, [Census](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-2010-state-virginia-2010-census-block-state-based#sec-dates)
  
- replication-final
  - shapefile produced by VA_MGGG_replication_file-census.ipynb
  
- MGGG-final
  - MGGG's VA shapefile. Downloaded 05/20/2020 from [mggg-states repo](https://github.com/mggg-states/VA-shapefiles)

