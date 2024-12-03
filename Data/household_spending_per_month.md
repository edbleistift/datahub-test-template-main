#### Household Spending per Month
<PlotlyBarChart
  data={{
    url: 'data/household_spending_per_month.csv'
  }}
  yAxis="household_spending_per_month"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/household_spending_per_month.csv'
  }}
/>

## Data 

Salary data collected by hand from stat.gov.kz stats: https://stat.gov.kz/ru/industries/environment/stat-eco/dynamic-tables/

We downoladed data from this source and placed it in the data folders 

We have processed the source data to make it normalized and derived  several aggregated datasets from it:

* `data/cost_piv.csv` - living space cost data
* `data/spend_piv.csv` - houshold spending per month 
* `datapackage.json` - conatins all of the key information about our dataset

## Scripts

* `cost.py` - our .py file to work with cost of the living space
* `spend.py` - our .py file to work with the average spendings of households
* `datapack.py` - creating datapckage.json file that conatinsall meatadata

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
