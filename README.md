# Hong Kong Voters Distribution [![Python](https://img.shields.io/badge/Program-Python-BLUE)](https://cydalytics.blogspot.com/) [![Folium](https://img.shields.io/badge/Package-Folium-GREEN)](https://cydalytics.blogspot.com/)
*<b>Created by cyda - Carrie Lo & Yeung Wong</b>*
![alt text](https://2.bp.blogspot.com/-JDCofS2Pvic/WxQCv_XstyI/AAAAAAAAABM/rWHKnG4ItnMULgmO_tWAuGTNL6kAexJlACK4BGAYYCw/s1000/tight%2Bbanner.png)

---------------------------------------------------------------------------------------------
### Please acknowledge <b>team cyda - Carrie Lo and Yeung Wong</b> when using the code

### If you find this script is helpful, please feel free to endorse us through Linkedin!
Linkedin:

* Carrie Lo - *https://www.linkedin.com/in/carrielsc/*
* Yeung Wong - *https://www.linkedin.com/in/yeungwong/*
---------------------------------------------------------------------------------------------
## Project Description
This project is to visualize Hong Kong voters distribution.

## Project Details
To check the tutorial article, please click [here](https://towardsdatascience.com/using-folium-to-generate-choropleth-map-with-customised-tooltips-12e4cec42af2).

The package used is `Folium`. Folium builds on the data wrangling strengths of the Python ecosystem and the mapping strengths of the `leaflet.js` library. To know more about the package, you can refer to the docunment [here](https://python-visualization.github.io/folium/).

Data were downloaded from [voter statistics](https://www.voterregistration.gov.hk/chi/statistic2019.html) and [census population statistics](https://www.censtatd.gov.hk/hkstat/sub/sp150.jsp?productCode=B1130301) released from Hong Kong Government and pre-processed. The data used in the map are stored in [Consolidated Data.xlsx](https://github.com/cydalytics/HK_Voters_Distribution/blob/master/Consolidated%20Data.xlsx). Feel free to play around =)

The original map json file of Hong Kong is downloaded from [this site](https://abhijeet.carto.com/tables/hkg_adm1/public/map).

## Demonstration

To test the interactive effects of the charts, please visit [https://cydalytics.blogspot.com/2020/05/hk-voter-analysis.html](https://cydalytics.blogspot.com/2020/05/hk-voter-analysis.html).

HK Map with Different TileLayers

![alt text](https://camo.githubusercontent.com/05a050621f46528cee4726adbebad05747bdb4f4/68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d49385953677a747161346f2f587251344d6444705f64492f41414141414141414146412f6d625771412d5356454c7379586d586d4b4936307654764a436e55376c58423541434c63424741735948512f733634302f53637265656e73686f74253242323032302d30352d3038253242617425324231322e33322e3130253242414d2e706e67)

HK Map with Customized Tooltip Version 1

![alt text](https://camo.githubusercontent.com/009fcc500544b6f1b1e05f2f38e107ac669d0dec/68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d48714c54415a64654f6d342f58725132727643475230492f41414141414141414145302f6c7866654e564b42676245344d374a4d4262704c7444325f7351634e3843494c77434c63424741735948512f733634302f53637265656e73686f74253242323032302d30352d3038253242617425324231322e30332e3336253242414d2e706e67)

HK Map with Customized Tooltip Version 2
 
![alt text](https://camo.githubusercontent.com/6a3bbe500580e8c9e7f0101ac788250795f7edbd/68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d7a5f485a3531684d49496b2f5872513272535f435452492f41414141414141414145772f396d5336707550467645672d5a4f713749634d674e6132664f6d5274334e796841434c63424741735948512f733634302f53637265656e73686f74253242323032302d30352d3038253242617425324231322e30342e3237253242414d2e706e67)
