# pandas-countries-analysis
# Countries Data Analysis with Pandas

A practice project where I answer 11 questions about countries around the world using **Python and Pandas**.

## Dataset

- File: `Countries.csv` (one row per country, 64 columns)
- Columns used include `country`, `country_long`, `capital_city`, `region`, `continent`, `population`, `democracy_score` and `political_leader`

## Pandas concepts practised

- Reading a CSV with `read_csv`, previewing with `head`
- Boolean filtering (`df[df['col'] == value]`)
- `max`, `min`, `nlargest`, `sort_values`
- `value_counts` and counting missing values with `isna`
- Using `apply` with a custom function on a text column
- Filtering a subset (Africa) and querying it

## Notes

- The `political_leader` column is a snapshot from when the dataset was created, so some leaders may have changed since.

## How to run

```bash
pip install pandas numpy jupyter
# keep Countries.csv in the same folder as the notebook
jupyter notebook project2_pandas_.ipynb
```

## Author

Arpita Singh 
