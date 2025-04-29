## About

This repository contains yearly-average population-weighted
PM<sub>2.5</sub> concentration levels for countries that was used for a
project and related publications on air quality knowledge (AQ-IQ) and
PM2.5 levels for the top 10 populous countries in the world. All data in
this public repository is free for use and download as they are
generated using open-source datasets. Pop-weighted yearly-average
PM<sub>2.5</sub> concentration levels are available for the top 10
populous countries in the world: Bangladesh, Brazil, China, India,
Indonesia, Mexico, Nigeria, Pakistan, Russia, and United States for the
years 2019 to 2021.

## Data sources used

1.  The global annual PM<sub>2.5</sub> concentration levels can be
    accessed from [Atmospheric Composition Analysis
    Group](https://sites.wustl.edu/acag/datasets/surface-pm2-5/#V5.GL.03).
2.  The maps files can be accesseed from
    [GADM](https://gadm.org/index.html).
3.  The global population distribution data can be accessed from
    [LandScan Global Population
    Database](https://www.eastview.com/resources/e-collections/landscan/).

## Variables

Example using highest spatial resolution (name3) for Bangladesh.

    BGD3 <- st_read("C:/Users/banan/NUS Dropbox/Li Na Ang/Li Na Ang’s files/Home/Github/pop-weighted-PM2.5_countries/Bangladesh/v5_BGD_name3.shp")

    ## Reading layer `v5_BGD_name3' from data source 
    ##   `C:\Users\banan\NUS Dropbox\Li Na Ang\Li Na Ang’s files\Home\Github\pop-weighted-PM2.5_countries\Bangladesh\v5_BGD_name3.shp' 
    ##   using driver `ESRI Shapefile'
    ## Simple feature collection with 545 features and 25 fields
    ## Geometry type: MULTIPOLYGON
    ## Dimension:     XY
    ## Bounding box:  xmin: 88.01057 ymin: 20.74111 xmax: 92.67366 ymax: 26.63407
    ## Geodetic CRS:  WGS 84

    names(BGD3)

    ##  [1] "GID_3"     "GID_0"     "COUNTRY"   "GID_1"     "NAME_1"    "NL_NAME_1" "GID_2"     "NAME_2"    "NL_NAME_2"
    ## [10] "NAME_3"    "VARNAME_3" "NL_NAME_3" "TYPE_3"    "ENGTYPE_3" "CC_3"      "HASC_3"    "PM25_2019" "pop_2019" 
    ## [19] "pwpm_2019" "PM25_2020" "pop_2020"  "pwpm_2020" "PM25_2021" "pop_2021"  "pwpm_2021" "geometry"

Variables of interest - NAME\_X = name of administrative unit for the
associated PM<sub>2.5</sub> concentration levels - PM25\_XXXX = raw
annual average PM<sub>2.5</sub> concentration levels for year XXXX -
pop\_XXXX = population density for year XXXX - pwpm\_XXXX = population
weighted average PM<sub>2.5</sub> concentration levels for year XXXX

## Bangladesh

    ##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
    ##   45.84   68.64   76.27   76.40   87.00   98.30

    ## Reading layer `v5_BGD_name3' from data source 
    ##   `C:\Users\banan\NUS Dropbox\Li Na Ang\Li Na Ang’s files\Home\Github\pop-weighted-PM2.5_countries\Bangladesh\v5_BGD_name3.shp' 
    ##   using driver `ESRI Shapefile'
    ## Simple feature collection with 545 features and 25 fields
    ## Geometry type: MULTIPOLYGON
    ## Dimension:     XY
    ## Bounding box:  xmin: 88.01057 ymin: 20.74111 xmax: 92.67366 ymax: 26.63407
    ## Geodetic CRS:  WGS 84

    ## Reading layer `v5_BGD_name2' from data source 
    ##   `C:\Users\banan\NUS Dropbox\Li Na Ang\Li Na Ang’s files\Home\Github\pop-weighted-PM2.5_countries\Bangladesh\v5_BGD_name2.shp' 
    ##   using driver `ESRI Shapefile'
    ## Simple feature collection with 64 features and 22 fields
    ## Geometry type: MULTIPOLYGON
    ## Dimension:     XY
    ## Bounding box:  xmin: 88.01057 ymin: 20.74111 xmax: 92.67366 ymax: 26.63407
    ## Geodetic CRS:  WGS 84

    ## Reading layer `v5_BGD_name1' from data source 
    ##   `C:\Users\banan\NUS Dropbox\Li Na Ang\Li Na Ang’s files\Home\Github\pop-weighted-PM2.5_countries\Bangladesh\v5_BGD_name1.shp' 
    ##   using driver `ESRI Shapefile'
    ## Simple feature collection with 8 features and 20 fields
    ## Geometry type: MULTIPOLYGON
    ## Dimension:     XY
    ## Bounding box:  xmin: 88.01057 ymin: 20.74111 xmax: 92.67366 ymax: 26.63407
    ## Geodetic CRS:  WGS 84

<img src="C:\Users\banan\NUS Dropbox\Li Na Ang\Li Na Ang’s files\Home\Github\pop-weighted-PM2.5_countries\README_files/figure-markdown_strict/unnamed-chunk-90-1.png" style="display: block; margin: auto;" />

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
