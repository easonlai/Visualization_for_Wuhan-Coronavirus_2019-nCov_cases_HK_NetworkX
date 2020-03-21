# Relationship visualization for Wuhan Coronavirus 2019-nCov cases Hong Kong with NetworkX
Relationship visualization for Wuhan Coronavirus (2019-nCov) cases in Hong Kong by [NetworkX](https://networkx.github.io/)

Source open data "Residential buildings in which probable/confirmed cases have resided in the past 14 days or non-residential building with 2 or more probable/confirmed cases in the past 14 days (English)" & "Details of probable/confirmed cases of COVID-19 infection in Hong Kong (English)" from [Centre for Health Protection Hong Kong (CHP)](https://www.chp.gov.hk/en/index.html) to build relationship dataset (hkcase_relationship.csv).

Relationship dataset last update on 21 Mar 2020.

* 0 = Imported from "Case classification" column in dataset "Details of probable/confirmed cases of COVID-19 infection in Hong Kong (English)"

* From dataset "Residential buildings in which probable/confirmed cases have resided in the past 14 days or non-residential building with 2 or more probable/confirmed cases in the past 14 days (English)", I take an assumption if infected person (case) are located in same building, they will be inter-infected as it haven't further details (e.g. sequence, mediums, etc...).

Other open data from CHP can be obtain from https://data.gov.hk/en-data/dataset/hk-dh-chpsebcddr-novel-infectious-agent.

![alt text](https://github.com/easonlai/Visualization_for_Wuhan-Coronavirus_2019-nCov_cases_HK_NetworkX/blob/master/network1.PNG)


Maybe with extra [Geo-tag data](https://github.com/easonlai/Visualization_for_Wuhan-Coronavirus_2019-nCov_cases_HK), can build more interesting relationship graph mapping with NetworkX.

![alt text](https://github.com/easonlai/Visualization_for_Wuhan-Coronavirus_2019-nCov_cases_HK_NetworkX/blob/master/network2.PNG)


Below is sample BI visualization from PowerBI (explore_with_powerbi_network.pbix)

![alt text](https://github.com/easonlai/Visualization_for_Wuhan-Coronavirus_2019-nCov_cases_HK_NetworkX/blob/master/network2_pbi.PNG)
