#### Crime Amount

<PlotlyBarChart
  data={{
    url: 'data/crime_amount.csv'
  }}
  yAxis="crime_amount"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/crime_amount.csv'
  }}
/>

## Data 

Salary data collected by hand from qamqor.gov.kz stats: https://qamqor.gov.kz/crimestat/statistics

We downoladed data from this source and placed it in the data folders 

We have processed the source data to make it normalized and derived  several aggregated datasets from it:

* `data/comb.csv` - final combined data about occured crime acts, that we later would use for graph
* `datapackage.json` - conatins all of the key information about our dataset

## Scripts

* `anim.py` - uses matplotlib to create an infographic
* `datapack.py` - creating datapckage.json file that conatinsall meatadata

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
