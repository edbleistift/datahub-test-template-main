#### Unemployment Rate
<PlotlyBarChart
  data={{
    url: 'data/unemployment_rate.csv'
  }}
  yAxis="unemployment_rate"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/unemployment_rate.csv'
  }}
/>

## Data 

Data is in xlsx format and synced with upstream source yearly. It is sourced from https://stat.gov.kz/en/industries/labor-and-income/stat-empt-unempl/

**Note:** Since stat.gov.kz requested for a signed key for authorization, we just downloaded and put in directory *archive*. It is temporary solution

We have processed the source data to make it normalized and derived from it several aggregated datasets:

* `data/unemploymentRate.csv` - data by segments.

We have also added some metadata such as column descriptions and [data packaged it][dp].

[dp]: https://frictionlessdata.io/data-package/


## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
