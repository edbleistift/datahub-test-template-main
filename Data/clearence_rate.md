#### Clearence Rate

<PlotlyBarChart
  data={{
    url: 'data/clearance_rate.csv'
  }}
  yAxis="clearance_rate"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/clearance_rate.csv'
  }}
/>



## Data 

Salary data collected by hand from qamqor.gov.kz stats: https://qamqor.gov.kz/crimestat/statistics

We downoladed data from this source and placed it in the data folders 

We have processed the source data to make it normalized and derived  several aggregated datasets from it:

* `data/output.csv` - final combined data
* `datapackage.json` - conatins all of the key information about our dataset

## Scripts

* `scripts/script.py` - our main script
* `datapack.py` - creating datapckage.json file that conatinsall meatadata

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
