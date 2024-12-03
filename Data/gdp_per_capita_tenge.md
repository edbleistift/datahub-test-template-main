#### GDP per Capita Tenge

<PlotlyBarChart
  data={{
    url: 'data/gdp.csv'
  }}
  yAxis="gdp_per_capita_tenge"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/gdp.csv'
  }}
/>

## Data 

Data collected from https://stat.gov.kz

We extracted the data from these sources and put it in the acrhive folder as quarters.xlsx .

We processed the original data to bring them back to normal, and extracted several aggregated datasets from them into the Data folder:

* `6. ВРП на душу населения.xlsx` - contains information of 2022 year 
* `datapackage.json` - contains all the key information about our dataset

## Scripts

* `process.py ` - runs the script

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
