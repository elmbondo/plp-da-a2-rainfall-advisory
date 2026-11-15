# plp-da-a2-rainfall-advisory
# County Rainfall and Planting Advisory

**Author:** Fidelmah Mbondo
**Cohort:** PLP Data Analytics 1 Million Devs Cohort

## Project summary

A farmer-support NGO sends SMS advice on planting windows in five counties. This project cleans a hand-typed Machakos rainfall row, combines the five counties into one NumPy array, and works out annual totals, monthly averages, wettest months, dry months and the best two-month planting window for each county. The results are saved in rainfall_summary.csv, written with the csv module.

## How to run

1. Install the library with pip install -r requirements.txt.
2. [Open in Colab](https://colab.research.google.com/github/elmbondo/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb), or open rainfall_analysis.ipynb in Jupyter.
3. Choose Runtime, then Run all. The notebook creates rainfall_summary.csv.

## Planting advisory

- Plant in April to May in Nairobi, Nakuru, Kisumu and Mombasa, where those two months bring the most rain (265 to 420 mm).
- Plant in November to December in Machakos (278 mm), and give Machakos farmers drought and water-saving advice, because it has 6 dry months and the lowest annual total (811 mm).
- Treat these dates as a guide only, because the data covers one year and two Machakos readings (April and September) were estimated at 68 mm.
