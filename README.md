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

  |Filename|	            IHA|	 Metric|	                                          Description|	                                                                       unit|
|---|---|----|----|---|
|metric__dh1__all_de	|  DH1|   Annual maxima of 1 day means of daily discharge|	 Magnitude of maximum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dh2__all_de	|  DH2|	  Annual maxima of 3 day means of daily discharge|	  Magnitude of maximum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dh3__all_de	|  DH3|	  Annual maxima of 7 day means of daily discharge|	  Magnitude of maximum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dh4__all_de	|  DH4|	  Annual maxima of 30 day means of daily discharge|	Magnitude of maximum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dh5__all_de	|  DH5|	  Annual maxima of 90 day means of daily discharge|	Magnitude of maximum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dl1__all_de	|  DL1|	  Annual minima of 1 day means of daily discharge	|  Magnitude of minimum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dl2__all_de	|  DL2|	  Annual minima of 3 day means of daily discharge	|  Magnitude of minimum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dl3__all_de	|  DL3|	  Annual minima of 7 day means of daily discharge|	  Magnitude of minimum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dl4__all_de	|  DL4|	  Annual minima of 30 day means of daily discharge|	Magnitude of minimum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__dl5__all_de	|  DL5|	  Annual minima of 90 day means of daily discharge|	Magnitude of minimum annual flow of various duration, ranging from daily to seasonal|	m3 s-1
|metric__ma1__all_de	|  MA1|	  Mean daily flows	                                |Mean daily flows	                                                                    |m3 s-1
|metric__ma2__all_de	|  MA2|	  Median daily flows	                              |Median daily flows	                                                                  |m3 s-1
|metric__ma12__all_de|	MA12|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma13__all_de|	MA13|	Mean monthly flows	                              |Mean monthly flow for all months	                                                     |m3 s-1
|metric__ma14__all_de|	MA14|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma15__all_de|	MA15|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma16__all_de|	MA16|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma17__all_de|	MA17|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma18__all_de|	MA18|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma19__all_de|	MA19|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma20__all_de|	MA20|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma21__all_de|	MA21|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma22__all_de|	MA22|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__ma23__all_de|	MA23|	Mean monthly flows	                              |Mean monthly flow for all months	                                                    |m3 s-1
|metric__mh1__all_de	|  MH1|  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh2__all_de	|  MH2|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh3__all_de	|  MH3|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh4__all_de	|  MH4|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh5__all_de	|  MH5|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh6__all_de	|  MH6|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh7__all_de	|  MH7|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh8__all_de	|  MH8|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh9__all_de	|  MH9|	  Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh10__all_de|	MH10|	Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh11__all_de|	MH11|	Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh12__all_de|	MH12|	Mean maximum monthly flows	                      |Mean of the maximum monthly flows for all months	                                    |m3 s-1
|metric__mh21__all_de|	MH21|	High flow volume	                                |Mean of the high flow volume (calculated as the area between the hydrograph and the upper threshold during the high flow event) divided by median annual daily flow across all years. The upper threshold is defined as 1 times median annual flow|   days |                                                                                                                                             
|metric__ml1__all_de|	  ML1|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml2__all_de|	  ML2|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml3__all_de|   ML3|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml4__all_de|	  ML4|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml5__all_de|	  ML5|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml6__all_de|	  ML6|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml7__all_de|	  ML7|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml8__all_de|	  ML8|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml9__all_de|	  ML9|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml10__all_de|	ML10|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml11__all_de|	ML11|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ml12__all_de|	ML12|	  Mean minimum monthly flows	                     | Mean minimum monthly flow for all months	                                            |m3 s-1
|metric__ra1__all_de|	  RA1|	  Rise rate	                                       | Mean rate of positive changes in flow from one day to the next	                     | m3 s-1 d-1
|metric__ra3__all_de|	  RA3|	  Fall rate	                                       | Mean rate of negative changes in flow from one day to the next	                      |m3 s-1 d-1
|metric__ta1__all_de|	  TA1|	  Constancy	                                        |See Colwell (1974)	                                                                  |dimensionless
|metric__ta2__all_de|	  TA2|	  Predictability of flow	                          |Composed of two independent, additivecomponents: constancy (a measure of temporal invariance) and contingency (a measure of periodicity)	       | dimensionless|
