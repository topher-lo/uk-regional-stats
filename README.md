# uk-regional-stats
Visualisation of regional U.K. statistics provided by the Office of National Statistics (ONS).

## TO DO:
    - [x] Extract relevant worksheets from ONS Excel data and save as csv files
    - [x] Convert ESRI shapefile from the Ordnance Survey into GeoDataFrame object and save as csv file
    - [ ] Create line charts
        - [ ] GVA per BIC excluding O, P and Q (1999-2019)
        - [ ] MFP per BIC excluding O, P and Q (1999-2019)
    - [ ] Create choropleths
        - [ ] GVA by NUTS3 regions (1999-2019)
        - [ ] Enterprises by turnover sizeband by NUTS3 regions (2020)
        - [ ] Enterprises by employment sizeband by NUTS3 regions (2020)
        - [ ] Income sources by NUTS3 regions (1998-2018)

## Data Sources:
- Multi-factor productivity estimates (7th July 2020) (https://www.ons.gov.uk/economy/economicoutputandproductivity/productivitymeasures/datasets/multifactorproductivityexperimentalestimatesreferencetables)
- UK business: activity, size and location (29th Sept 2020) (https://www.ons.gov.uk/businessindustryandtrade/business/activitysizeandlocation/datasets/ukbusinessactivitysizeandlocation)
- Regional gross value added (balanced) by industry: all NUTS level regions (19th Dec 2019) (https://www.ons.gov.uk/economy/grossvalueaddedgva/datasets/nominalandrealregionalgrossvalueaddedbalancedbyindustry)
- Regional gross disposable household income: all NUTS level regions (4th June 2020) (https://www.ons.gov.uk/economy/regionalaccounts/grossdisposablehouseholdincome/datasets/regionalgrossdisposablehouseholdincomegdhi)
- Boundary-line ESRI shapefile (October 2020) (https://osdatahub.os.uk/downloads/open/BoundaryLine)
