#### Total City Population
<PlotlyBarChart
  data={{
    url: 'data/total_city_population.csv'
  }}
  yAxis="Total_city_population"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/total_city_population.csv'
  }}
/>

## Data

Population data is sourced from [stat.gov](https://stat.gov).

- `archive/source.xlsx`: Raw data of population of Kazakhstan as of January 1, 2023.
- `data/city_population.csv`: Cleaned version containing population information in regions and three major cities of Kazakhstan.

## Scripts

- `package.py`: Used to create or update the datapackage.json file containing metadata about the dataset.
- `transform.py`: Used to convert the source.xlsx file to a CSV format for easier processing.

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License](https://www.opendatacommons.org/licenses/pddl/1-0/ "‌").
