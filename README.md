# Indian economy study, 2000 to 2025

I wanted to see how India's economy actually moved over the last 25 years, so I pulled four indicators from the World Bank and put them side by side: GDP growth, inflation, FDI inflows and forex reserves.

## What I found

GDP growth took two big hits, in 2008 when it dropped to about 3.1% and in 2020 when it shrank 5.8% during COVID. Both times it came back within a year, and since 2022 it has stayed around 7 to 7.6%.

Inflation peaked at around 12% in 2010 and has mostly come down since then. 2025 is the lowest in the whole series at 2.4%.

FDI is the part that surprised me. As a share of GDP it was 2.4% in 2020 but only 0.7 to 1.0% from 2023 to 2025. Part of that could just be GDP growing faster, so I still need to check FDI in actual dollar terms before saying it really fell.

Forex reserves went from about 40 billion dollars in 2000 to about 700 billion in 2025, so India has a much bigger cushion against currency shocks now.

The charts and the questions I want to look at next are in [economy_india.ipynb](economy_india.ipynb).

## Data

World Bank, World Development Indicators, pulled through the World Bank API in October 2026.

Indicator codes used: `NY.GDP.MKTP.KD.ZG` (GDP growth), `FP.CPI.TOTL.ZG` (inflation), `BX.KLT.DINV.WD.GD.ZS` (FDI inflows), `FI.RES.TOTL.CD` (total reserves). The latest year's figures can still get revised.

## How to run

```
pip install -r requirements.txt
```

Then open `economy_india.ipynb` and run all cells. The data loads straight from the API, so you need an internet connection.
