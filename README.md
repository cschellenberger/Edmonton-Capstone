# Edmonton Open Data Analysis for Property Assessment Values and Crime
<div>
  <img src="https://s3-us-west-2.amazonaws.com/schellenbergers3bucket/crime+vs+population.png" alt="crime vs pop" height="200"> <img src="https://s3-us-west-2.amazonaws.com/schellenbergers3bucket/map-analysis.png" alt="map analysis" height="200"> <img src="https://s3-us-west-2.amazonaws.com/schellenbergers3bucket/survey-responses.png" alt="survey analysis" height="200">
</div>

****
# Documentation

## [Edmonton Property Assessment Report](https://github.com/cschellenberger/Edmonton-Capstone/blob/master/Edmonton%20Property%20Assessment%20and%20Crime%20Report.pdf)
****

# iPython Notebooks
Notebook | Description
-------- | -----------
[Survey Analysis](https://github.com/cschellenberger/Springboard/blob/master/capstone/Survey%20Analysis.ipynb) | A statistical analaysis of community response data. Producing 99% confidence intervals regarding property assessment responses 
[Data Wrangling](https://github.com/cschellenberger/Springboard/blob/master/capstone/Data%20Wrangling.ipynb) | Data cleaning, organization, transformation, and preparation for analysis
[Map Analysis](https://github.com/cschellenberger/Springboard/blob/master/capstone/Map%20Analysis.ipynb) | A visual (Geographical Information System) representation of the property assessment data
[Regressor Selection](https://github.com/cschellenberger/Springboard/blob/master/capstone/Regressor%20Selection.ipynb) | Model optimization utilizing the Hyperopt module for regressor selection
[Machine Learning](https://github.com/cschellenberger/Springboard/blob/master/capstone/Machine%20Learning.ipynb) | Predictive analysis of property assessment values

# Datasets
  - *Property_Assessment_Data__Current_Calendar_Year_.csv* [Data Source](https://data.edmonton.ca/City-Administration/Property-Assessment-Data-Current-Calendar-Year-/q7d6-ambg)

  - *EPS_Neighbourhood_Criminal_Incidents.csv* [Data Source](https://dashboard.edmonton.ca/dataset/EPS-Neighbourhood-Criminal-Incidents/xthe-mnvi)

  - *Property_Information_Data__Current_Calendar_Year_.csv* [Data Source](https://data.edmonton.ca/City-Administration/Property-Information-Data-Current-Calendar-Year-/dkk9-cj3x) The city presents property data but does not guarantee its accuracy.

  - **Historical Property Assessment Data** - 2012-2017 **Large Dataset \(2.18M records & 252.7MB\)** — *Property_Assessment_Data__2012_-_2017_.csv* [Data Source](https://data.edmonton.ca/City-Administration/Property-Assessment-Data-2012-2017-/qi6a-xuwt)

  - *Property_Assessment__Customer_Service__-_Edmonton_Insight_Community.csv* [Data Source](https://data.edmonton.ca/Surveys/Property-Assessment-Customer-Service-Edmonton-Insi/x9sw-zhhj) This survey is analyzed to cultivate some understanding of the publics response to assessment practices in 2018.
  
  - *2016_Census_-_Population_by_Citizenship__Neighbourhood_Ward_.csv* [Data Source](https://data.edmonton.ca/Census/2016-Census-Population-by-Citizenship-Neighbourhoo/2g4b-ti2n) The most recent and complete population data is from the 2016 census and is aggregated by neighbourhood and citizenship. For the purposes of providing insight into property assessments we exclude citizenship segregation.
  
