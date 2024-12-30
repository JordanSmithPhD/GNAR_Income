# GNAR_Income
Code used to acquire, process, and analyze all data reported in 'Income growth and inequality in gateway communities throughout the American West'.

The repository consists of three Python notebooks, which must be executed sequentially to replicate the analysis.

1. ACS_data_download.ipynb - Downloads and processes all American Community Survey 5-year estimates.
2. spatial_metrics_and_visitation_data_download.ipynb - Calculates all spatial metrics, downloads all park visitation data, and prepares the data for analysis.
3. analysis.ipynb - Conducts all analysis reported in the paper.

All code is intended to be run in Google Colab with limited need to save/retrieve local files. A local repository structured identical to the one below will allow for direct replication. The necessary data files within each sub-folder must be downloaded from their respective repository prior to analysis.

LOCAL FOLDER
 - NPS
 - - NPS_-_Points_of_Interest_(POIs)_-_Geographic_Coordinate_System
 - - - NPS_-_Points_of_Interest_(POIs)_-_Geographic_Coordinate_System.shp (and supporting files) available from: https://public-nps.opendata.arcgis.com/datasets/a40e2faa953b4c5cb7fe10004dc3008e_0/explore?location=2.902345%2C-12.488250%2C2.33
 - - nps_boundary.shp (and supporting files) available from: https://public-nps.opendata.arcgis.com/datasets/nps::nps-land-resources-division-boundary-and-tract-data-service/explore?layer=2&location=4.125801%2C-12.497900%2C2.52
 - ACS_Data
 - - Spatial
 - - - tl_2022_56_place
 - - - - tl_2022_56_place.shp (and supporting files) available from: https://www2.census.gov/geo/tiger/TIGER2023/PLACE/ *same for all place boundary files below*
 - - - tl_2022_53_place
 - - - - tl_2022_53_place.shp (and supporting files)
 - - - tl_2022_49_place
 - - - - tl_2022_49_place.shp (and supporting files)
 - - - tl_2022_41_place
 - - - - tl_2022_41_place.shp (and supporting files)
 - - - tl_2022_35_place
 - - - - tl_2022_35_place.shp (and supporting files)
 - - - tl_2022_32_place
 - - - - tl_2022_32_place.shp (and supporting files)
 - - - tl_2022_30_place
 - - - - tl_2022_30_place.shp (and supporting files)
 - - - tl_2022_06_place
 - - - - tl_2022_06_place.shp (and supporting files)
 - - - tl_2022_16_place
 - - - - tl_2022_16_place.shp (and supporting files)
 - - - tl_2022_08_place
 - - - - tl_2022_08_place.shp (and supporting files)
 - - - tl_2022_04_place
 - - - - tl_2022_04_place.shp (and supporting files)
 - - - tl_2022_02_place
 - - - - tl_2022_02_place.shp (and supporting files)
 - Figures
 - - Figure 1
