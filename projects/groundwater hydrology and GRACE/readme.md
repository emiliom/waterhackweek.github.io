### Project Title: Data exploration using GRACE remotely derived groundwater levels and well point datasets 


#### The problem

Tools are needed to connect remote sensing data that varies in space and time to point measurements at specific locations and time intervals. The integration of satellite missions (GRACE) with hydrology models for determining drought indicators and water levels has been done in the United States (Houborg, et al., 2012; Zaitchick et al., 2008) using data assimilation from sophisticated observatory networks that are not available, for example, in sub-saharan Africa. Studies have analyzed operational, technical, institutional, financial, and environmental predictors of functionality for groundwater access (well) data collected from over 25,000 community-managed handpumps in Liberia, Sierra Leone, and Uganda (Foster (2013)). Lahren and Cook (2016) code and analyze the reasons for failure in 250,000 water points in 25 countries and found that 30% of boreholes are not functioning, either for "technical or mechanical” reasons, or for "low quantity".   According to the World Bank, water supply failure in Africa is estimated to “represent a lost investment in excess of $1.2 billion” (Bonsor et. al. 2015).  Women and girls continue to be the world’s water collectors, spending a significant fraction of their time and energy on the task (Sorenson et al 2011, Graham et al 2016, Cook et al 2016). Can a planetary observational tool be used to understand groundwater access and vulnerability for domestic use in rural households? If so, we can further investigate and develop the GRACE for Girls project.


#### Application Example

In areas where domestic water access is primarily through wells, are areas with non-functional wells because of low quantity observable with remote sensing data?   

What spatial statistics can be used to understand the reasons for well failure using geolocated water points and  falling groundwater levels? 

In recent years, NGOs, as well as governments and academics, have begun collecting water point data in an effort to not only monitor functionality, but to understand the relationship between determining factors and failure of handpumps.   “Low quantity” is cited as a reason in 43% of failed boreholes (where some failure reason was given) in Lahren and Cook (2016).  But poor yield can be due to a number of different factors, including poor siting, mechanical failure, or hydrological scarcity. Some studies have pointed the finger at poor community participation and low user demand (McPherson and McGarry 1987; Isham et. al. 1995), poor construction quality and siting (RWSN 2010; Harvey 2004; Danert 2013), and low capacity of communities to raise the necessary finances for repair or difficulty in accessing spare parts (Skinner et. al. 2002; Franceys & Pezon 2010; Schweitser & Mihelcic 2012).  The data supporting these analyses, however, has typically been specific to regions or countries, or anectodal.  The proposed project will attempt to leverage externally-derived measures of groundwater abstraction using GRACE to determine what fraction of non-functionality can reasonably be attributed to falling groundwater levels and low water availability. 

These spatial datasets provide new opportunities to: 
1) understand the relationship between GRACE grid cell water level trends and well point datasets that have been identified by Lahren and Cook (2016) as identified as a failure due to a hydrologic deficit/low quantity. 
2) understand the correlation between well functionality status and GRACE water level trends in locations where GRACE estimates decreasing trends.
3) understand the correlation between well functionality and GRACE trends in various African countries (or other subset of well data).

#### Sample data

How much is hydrological scarcity contributing to handpump failure in Africa?

Remote sensing data: The Gravity Recovery and Climate Experiment ( [GRACE:joint mission of NASA and the German Aerospace Center](http://www.csr.utexas.edu/grace/) ) measures the Earth's gravity anomalies to study how mass is distributed around the planet and used for studying Earth's eceans, geology, and climate. [Faisal - more details on data product here]

Point data: The Water Point Data Exchange ([WPDx](https://www.waterpointdata.org/)) is a global platfrom for sharing water point data to understand water services with 240,000 + water points in the dataset with the quantity of data varying between government support for complete datasets (all 101,000 water points in Uganda) as well as data in other countries with known GRACE observable groundwater levels (India).  

The WPDx data downloaded in February 2016, and coded for well failure due to water resources issues (Lahren and Cook (2016)), is provided on [Hydroshare](www.hydroshare.org). Go to Collaborate. Ask to Join Freshwater Group. Click on link for Freshwaterhack of UWGeohackweek.  Go to Collection Contents. Click on Freshwaterhack Project: Groundwater Resources and GRACE

#### Existing methods

[TO DO]
How do people generally work with these data? 

What are some of the drawbacks and challenges?

#### Project Ideas 

1) Identify and use spatial statistics to characterize well data with well failure due to a hydrologic deficit/low quantity. Identify whether a spatial correlation exists between non-functional wells and decreasing groundwater trends from GRACE. 

2) Identify and use spatial statistics to characterize where GRACE predicts decreasing groundwater trends. Explore the WPDx data variables and locations to identify any correlations. 

3) Identify any country specific correlations or trends in the well point database and GRACE. 


#### Potential tools:

* [scikit-learn](http://scikit-learn.org/stable/index.html)
* Earth System Modeling Framework Python interface: [ESMPy](https://www.earthsystemcog.org/projects/esmf/)

<img src = "https://github.com/geohackweek/geohackweek.github.io/blob/master/img/ndarray_icon.png" width = "60"> [xarray](https://geohackweek.github.io/nDarrays/)


#### Background reading: 
* Bonsor, H. C., Oates, N., Chilton, P. J., Carter, R. C., Casey, V., Macdonald, A. M., … Bennie, M. (2015). UPGro Catalyst Grant Report - A Hidden Crisis: strengthening the evidence base on the sustainability of rural groundwater supplies – results from a pilot study in Uganda.

* Cook, J., Kimuyu, P., & Whittington, D. (2016). The costs of coping with poor water supply in rural Kenya. Water Resources Research, 52, 841–859.

* Danert, K., Armstrong, T., Adelike, D., Daffau, B., Quedraogo, I., & Kwei, C. (2010). Code of Practice for Cost Effective Boreholes, (June). Retrieved from http://www.rural-water-supply.net/en/resources/details/128

* Foster, T. (2013). Predictors of sustainability for community-managed handpumps in sub-saharan Africa: Evidence from Liberia, Sierra Leone, and Uganda. Environmental Science and Technology, 47(21), 12037–12046. http://doi.org/10.1021/es402086n

* Franceys, R. and C. Pezon, 2010.  Services are forever: the importance of capital maintenance (CapManEx) in ensuring sustainable WASH services. WASHCost Briefing Note 1b.

* Graham, J. P., Hirai, M., & Kim, S.-S. (2016). An Analysis of Water Collection Labor among Women and Children in 24 Sub-Saharan African Countries. Plos One, 11(6), e0155981. http://doi.org/10.1371/journal.pone.0155981

* Harvey, P. A., Skinner, B. H., & Reed, R. A. (2002). Sustaining handpumps in Africa : lessons from Zambia and Ghana. Sustainable Environmental Sanitation and Water Services, 101–104.

* Harvey, P. A. (2004). Borehole sustainability in rural Africa : an analysis of routine field data. In Proceedings of the 30th WEDC conference.

* Houborg, R., M. Rodell, B. Li, R. Reichle, and B. Zaitchik, Drought indicators based on model assimilated GRACE terrestrial water storage observations, Wat. Resour. Res., 48, W07525, doi:10.1029/2011WR011291, 2012.

* Isham, J., Narayan, D., & Pritchett, L. (1995). Does participation improve performance? Establishing causality with subjective data. World Bank Economic Review, 9(2), 175–200. http://doi.org/10.1093/wber/9.2.175

* McPherson, H. J., & McGarry, M. G. (1987). User participation and implementation strategies in water and sanitation projects. International Journal of Water Resources Development, 3(1), 23–30. http://doi.org/10.1080/07900628708722330

* Rwsn. (2009). Myths of the Rural Water Supply Sector. Rural Water Supply Network Perspectives, (4).

* Rural Water Supply Network. (2013). Experiences and Ideas from RWSN’ s Sustainable Groundwater Community, (November 2012).

* Rural Water Source Network. (2014). Water Point Mapping : Indicators , pump functionality , accuracy of GPS , using and sharing data, (June), 1–9.

* Schweitzer, R. W., & Mihelcic, J. R. (2012). Assessing sustainability of community management of rural water systems in the developing world. Journal of Water, Sanitation and Hygiene for Development, 2(1), 20. http://doi.org/10.2166/washdev.2012.056

* Sorenson, S. B., Morssink, C., & Campos, P. A. (2011). Safe access to safe water in low income countries: Water fetching in current times. Social Science & Medicine, 72(9), 1522–1526. Retrieved from http://www.sciencedirect.com/science/article/pii/S0277953611001572

* Zaitchik, B.F., M. Rodell, and R.H. Reichle, Assimilation of GRACE terrestrial water storage data into a land surface model: results for the Mississippi River Basin, J. Hydrometeor., 9 (3), 535-548, doi:10.1175/2007JHM951.1, 2008.
