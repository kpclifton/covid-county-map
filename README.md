# covid-county-map

**Link to hosted app:** https://kpclifton.shinyapps.io/COVID-19_CountyMap/

## Description
This shiny app display maps of COVID-19 cases by counties for select US states and the District of Columbia. Currently, users can select Maryland, Pennsylvania, Virginia or DC. The counties are those defined by the U.S. Census Bureau which actually includes counties and some independent cities.  When the user hovers over a locality, the user sees the locality's name and its number of cases. The number of cases is generally reported as the number of positive tests among people tested but the definition can differ by state and is not clearly explained for every state.

All of the data gathered was publicly available. The sources are listed below. The aggregated data is available in this github repo as `covid_countydata.csv`. The Urban Institute's R package `urbnmapr` provided the county shapefiles. (https://medium.com/@urban_institute/how-to-create-state-and-county-maps-easily-in-r-577d29300bb2)
               
## Sources for COVID-19 cases:
- Maryland COVID-19 Case Map Dashboard: https://coronavirus.maryland.gov/
- COVID-19 in Virginia: http://www.vdh.virginia.gov/coronavirus/
- District of Columbia Coronavirus Data: "https://coronavirus.dc.gov/page/coronavirus-data
- COVID-19 Testing in Pennsylvania: https://www.health.pa.gov/topics/disease/coronavirus/Pages/Cases.aspx

## Sources for county FIPS codes:
- Virginia: https://www.cccarto.com/fipscodes/virginia/
- Maryland: https://web.archive.org/web/20040928115157/http://www.epa.gov/enviro/html/codes/md.html
- Pennsylvania: https://data.pa.gov/Government-That-Works/Federal-Information-Processing-Standard-FIPS-Codes/44ch-j9ei

