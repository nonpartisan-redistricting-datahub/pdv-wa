# vest-wa-2020

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-washington-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## **Accessible Files:**
- VEST WA 20 data file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=5007851&version=21.0)
  - Accessed: 10/20/21

- VEST WA 20 documentation file
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=5206372&version=21.0)
  - Accessed: 10/20/21

- WA 20 Precinct-Level Results
  - Online: [Washington Secretary of State](https://www.sos.wa.gov/elections/research/2020-general-election.aspx)
  - Accessed: 10/20/21
  - Note: These can be downloaded by clicking "GIS Ready Precinct Results".
    
- WA Precinct Shapefile
  - Online: [[Washington Secretary of State]](https://www.sos.wa.gov/elections/research/precinct-shapefiles.aspx)
  - Accessed: 10/20/21
  - Note: Download "Statewide_Precincts_2020General.zip".

- WA Cartographic Boundary File
  - Online: [US Census](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)
  - Accessed: 10/20/21
  - Note: Download "cb_2018_us_county_5m.zip". This file was not needed for the validation, but used because we suspected VEST clipped their precinct shapefile using a cartographic boundary file.

## File processing

- `vest-wa-2020-validation.ipynb` - documentation in markdown cells and comments
