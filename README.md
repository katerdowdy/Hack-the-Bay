# Hack the Bay: Data
This repo is intended to provide primary datasets and starter code for the Hack the Bay hackathon. 

## Recommended Datasets
X = primary dataset (strongly recommended)
o = optional (suggested)

| Source | Dataset | Challenge 1 | Challenge 2 | Challenge 3 | Challenge 4 |
|--------|---------|-------------|-------------|-------------|-------------|
| CBP / CMC | Water Quality | X | X | X | X |
| CBP / CMC | Benthic | o | o | o | o |
| USGS | [Stream Flow](https://waterdata.usgs.gov/nwis/rt) | o | o | o | |
| USGS | [Pollution Yields and Loads](https://cbrim.er.usgs.gov/trends_query.html?sorts%5Bstaid%5D=1&sorts%5Bpcode%5D=1&sorts%5Bstart_Year%5D=1&sorts%5Bend_Year%5D=1&sorts%5Bnyears%5D=1&sorts%5Bperiod%5D=1&sorts%5Blowf%5D=1&sorts%5Bestf%5D=1&sorts%5Bupf%5D=1&sorts%5Bfnt_Pct%5D=1&sorts%5BtrendDir%5D=1&sorts%5Blikelihood%5D=1) | o | | o | |
| USGS | [Geology](https://ngmdb.usgs.gov/Prodesc/proddesc_9215.htm) | o | | o | |
| NOAA | [Weather](https://www.ncdc.noaa.gov/cdo-web/) | | | o | |
| CBP | [Nutrient Point Source Database](https://www.chesapeakebay.net/what/downloads/bay_program_nutrient_point_source_database) | o | | o | |
| CBP | [Land Cover](ftp://ftp.chesapeakebay.net/pub/Geographic/ChesapeakeBay/Landcover/) | o | o | o | |
| CBP | [Public Access Data](ftp://ftp.chesapeakebay.net/pub/Geographic/BayRecreationalSites/) | | | | o |
| Chesapeake Conservancy | [Land Use](https://chesapeakeconservancy.org/conservation-innovation-center/high-resolution-data/land-use-data-project/) | X | | X | |
| EPA | [Environmental Justice (EJ) Screen](https://ejscreen.epa.gov/mapper/) | | | | o |
| CDC | [Social Vulnerability Index](https://svi.cdc.gov/data-and-tools-download.html) | | | | o |
| US Census | [Demographic / Economic Data](https://www.census.gov/data.html) | | | | o |
| US Census | [County Boundary Maps](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-nation-u-s-current-county-and-equivalent-national-shapefile) | | | | X |
| USDA | [HUC12 Boundary Maps](https://nrcs.app.box.com/v/huc/file/532373547877) | X | X | X | o |

## Contents
1. Data (Use this for Analysis)
  a. CMC water quality
    - See the explanation of parameter codes here
    - See the data dictionary here: https://www.chesapeakemonitoringcoop.org/wp-content/uploads/2020/07/Data-Dictionary_June-2020.pdf
  b. CBP water quality
    - See the explanation of parameter codes here
    - See the full data dictionary here: https://www.chesapeakebay.net/documents/3676/cbwqdb2004_rb.pdf
  c. CMC benthic samples
    - See the data dictionary here: https://www.chesapeakemonitoringcoop.org/wp-content/uploads/2020/07/Data-Dictionary_June-2020.pdf
2. Code
  a. Joining tables: this notebook walks through the process for joining the CMC and CBP export data into one table for each data source/type.
  b. EDA: this notebook contains preliminary EDA on 
