# stream_flow
Daily stream flow and hydrological metrics for Germany, as predicted by a simple regression model

Katie Irving1, Mathias Kuemmerlen2, Jens Kiesel1, Karan Kakouei1, Sami Domisch1, Sonja C. Jähnig1
1Department of Ecosystem Research, Leibniz-Institute of Freshwater Ecology and Inland Fisheries (IGB), Müggelseedamm 310, 12587 Berlin, Germany
2Department Systems Analysis, Integrated Assessment and Modelling, Eawag, Überlandstrasse 133, CH-8600 Dübendorf, Switzerland

Corresponding author: Katie Irving (irving@igb-berlin.de)

General information:
=====================
Stream flow data

All 64 layers are available as netCDF-4 files, where each file contains one year of daily stream flow (m3s-1) for the German stream network. To obtain the original values, the data have to be divided by 10,000. See the example R-script number (3) to load the files into R. Filenames are set as day-year-month-day_all_de.r, i.e.  “day_2013-12-31_all_de.r”

Extent: 5.866667, 15.03333, 47.29167, 54.90833  (xmin, xmax, ymin, ymax)

Cell size: 0.0083333333 degree (30 arcsec)
Projection: WGS84
Number of columns: 1100
Number of rows: 914
Number of layers: 365 or 366 if leap year
Pixel type: Int4S 
NoData value: -999 (Int4S) 


IHA metrics

All 53 metrics are available as netCDF-4 files, where each layer contains one metric for the German stream network. 

Extent: 5.866667, 15.03333, 47.29167, 54.90833  (xmin, xmax, ymin, ymax)

Cell size: 0.0083333333 degree (30 arcsec)
Projection: WGS84
Number of columns: 1100
Number of rows: 914
Pixel type: Int4S 
NoData value: -999 (Int4S) 

IHA Metric description


