#### Med Institutions Amount
<PlotlyBarChart
  data={{
    url: 'data/med_institutions_amount.csv'
  }}
  yAxis="med_institutions_amount"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/med_institutions_amount.csv'
  }}
/>

## Data

Medical institution data is sourced from [gender.stat.gov.kz](https://gender.stat.gov.kz/page/frontend/detail?id=68&slug=-55&cat_id=3&lang=ru):

- `archive/source.xls`: Raw data of medical institutions by region from 2000 to 2022.
- `data/med_institutions.csv`: Cleaned version containing data only for 2022 and translated to English.

## Scripts

- `package.py`: Used to create or update the datapackage.json file containing metadata about the dataset.
- `transform.py`: Used to convert the source.xls file to a CSV format for easier processing.

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
