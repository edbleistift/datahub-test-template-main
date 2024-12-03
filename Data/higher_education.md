#### Higher Education
<PlotlyBarChart
  data={{
    url: 'data/higher_education.csv'
  }}
  yAxis="Higher_Education"
  xAxis="Region"
/>

<FlatUiTable
  data={{
    url: 'data/higher_education.csv'
  }}
/>


## Data

Education data is sourced from ([stat.gov.kz](https://stat.gov.kz/upload/iblock/3a8/7c99zhdr5fpt1htbcd1migx7aqgazend/%D0%9E%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.pdf)).

- `document.pdf`: The original document containing the data about the education levels in Kazakhstan.
- `source.csv`: Raw data of population age 10 and older with higher education degrees by region for the year 2021. The 2022 data was not available from credible sources, hence the dataset focuses on 2021.
- `higher_education.csv`: English version containing data of population percentages with higher education degrees in urban areas only in 2021.

All percentage values are given relative to the total population aged 10 and older.

**Note:** The values for the Abai, Jetisu, and Ulytau regions are based on the broader location they are part of, due to specific data unavailability for these regions. For example, Jetisu's figures are included with those of the Almaty region.

## Scripts

- `package.py`: Used to create or update the `datapackage.json` file containing metadata about the dataset.
- `transform.py`: Used to convert the `source.csv` file for easier processing.

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License](https://www.opendatacommons.org/licenses/pddl/1-0/ "‌").
