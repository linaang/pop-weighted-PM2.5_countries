Population-weighted PM2.5 for countries
================
Lina Ang
2025-04-29

- [About](#about)
- [Data sources used](#data-sources-used)
- [Variables](#variables)
  - [Variables of interest](#variables-of-interest)
- [Bangladesh](#bangladesh)
- [Contact](#contact)

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

    ##  [1] "GID_3"     "GID_0"     "COUNTRY"   "GID_1"     "NAME_1"    "NL_NAME_1" "GID_2"     "NAME_2"    "NL_NAME_2"
    ## [10] "NAME_3"    "VARNAME_3" "NL_NAME_3" "TYPE_3"    "ENGTYPE_3" "CC_3"      "HASC_3"    "PM25_2019" "pop_2019" 
    ## [19] "pwpm_2019" "PM25_2020" "pop_2020"  "pwpm_2020" "PM25_2021" "pop_2021"  "pwpm_2021" "geometry"

### Variables of interest

1.  **NAME_X** = name of administrative unit for the associated
    PM<sub>2.5</sub> concentration levels
2.  **PM25_XXXX** = raw annual average PM<sub>2.5</sub> concentration
    levels for year XXXX
3.  **pop_XXXX** = population density for year XXXX
4.  **pwpm_XXXX** = population weighted average PM<sub>2.5</sub>
    concentration levels for year XXXX

## Bangladesh

<figure>
<img
src="C:/Users/banan/NUS%20Dropbox/Li%20Na%20Ang/Li%20Na%20Ang’s%20files/Home/Github/pop-weighted-PM2.5_countries/README_figures/BGD.jpg"
alt="2021 Population-weighted PM2.5 Bangladesh" />
<figcaption aria-hidden="true">2021 Population-weighted PM2.5
Bangladesh</figcaption>
</figure>

## Contact

<div style="text-align: justify; line-height: 1.8">

For more information, please email me at <ephanli@nus.edu.sg>.

</div>
