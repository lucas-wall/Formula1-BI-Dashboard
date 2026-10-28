# 🏎️ Formula 1 Analytics | Power BI, 70+ years of racing data

Interactive Power BI dashboard on Formula 1 history. The Kaggle World Championship dataset (14 tables) was merged into a single flat file of race results, covering seasons from 1950 to 2024, and modeled in Power BI to explore driver, team and circuit performance across the decades.

## Stack
`Power BI` `Power Query` `CSV` `Kaggle`

## What it does
- Consolidates 14 source tables (races, circuits, drivers, constructors, results, standings) into `formula1_merged_data.csv`, about 26.5k rows.
- Analyzes driver and team performance over time: wins, points, grid vs finishing position, championship standings.
- Shows race-level details such as circuit, country, laps and fastest lap time and speed.
- Uses a custom F1-inspired theme (team colors in `Design/F1_Palette.txt`), icons and background layouts in `Design/`.
- Documents context, methodology and conclusions in `Report.txt`.

## How to open / run
1. Clone the repo:
   ```bash
   git clone https://github.com/lucas-wall/Formula1-BI-Dashboard.git
   ```
2. Open `F1.pbix` in Power BI Desktop.
3. If prompted, point the data source to `formula1_merged_data.csv` in the repo root and click Refresh.
4. To explore the raw data, open `formula1_merged_data.csv` in any spreadsheet tool or load it with pandas.

## Repo layout
- `F1.pbix` - the Power BI report
- `formula1_merged_data.csv` - merged dataset
- `Report.txt` - project report
- `Design/` - background (`Background/`), icons (`Icons/`) and color palette (`F1_Palette.txt`)

## Data source
[Formula 1 World Championship (1950 - 2020), Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
