
# mggg-va
Replication files and data for [MGGG's VA](https://github.com/mggg-states/VA-shapefiles) shapefile.


# folder files

- VA_MGGG_replication_file.ipynb
  - processing file for reproducing MGGG’s VA shapefile with the data MGGG described
  
- VA_MGGG_replication_file-census.ipynb  (suggested for use)
  - processing file for reproducing MGGG’s VA shapefile using Census demographic data
  
- verification folder
  - folder that contains verification replication file (VA_verify.ipynb) and report outputs


On AWS:

- raw-from-source 
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



Detailed data [documentation](https://docs.google.com/document/d/1znwnPC_X9tJucH59zYJl_5CPiSR29LWEJajGQ7hENPA/edit)
    
[Final write-up](https://docs.google.com/document/d/1sNtZLH5gajJJE0otnZCKDiCM8aqThyyd1Qa__MxLvss/edit?usp=sharing) on the replication process

[Verification write-up](https://docs.google.com/document/d/1NupGPxH0I2JuPmHzMSoFjzcDV7msq5fi2gyQy5GPxng/edit?usp=sharing)
