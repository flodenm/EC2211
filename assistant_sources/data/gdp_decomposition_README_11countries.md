# GDP per capita decomposition data

These files reproduce and extend the decomposition used in Banque de France,
*Revisiting the European performance gap vis-à-vis the United States*.

## Country coverage

United States, Germany, France, Italy, Sweden, Denmark, Finland, Netherlands,
Belgium, Spain, and Austria. The files cover 2000–2025 where the underlying
AMECO data are available.

The accounting identity is

Y/P = (Y/H) × (H/L) × (L/A) × (A/P),

where **Y** is real GDP, **P** total population, **H** total annual hours worked,
**L** employment (persons), and **A** population aged **15–74**.

## Files

### `gdp_decomposition_relative_11countries.csv`

The five components are indexed against the United States in the same year
(US = 100):

- `gdp_per_capita_us100` = Y/P
- `gdp_per_hour_us100` = Y/H
- `hours_per_worker_us100` = H/L
- `workers_per_working_age_us100` = L/A
- `working_age_share_us100` = A/P

### `gdp_decomposition_levels_11countries.csv`

The corresponding non-indexed levels:

- GDP per capita: **constant 2015 PPS per person**
- GDP per hour: **constant 2015 PPS per hour worked**
- hours per worker: annual hours
- workers / population aged 15–74: fraction
- population aged 15–74 / total population: fraction

## GDP, currencies, and the fixed 2015 PPP conversion

The GDP series are **not first converted into current US dollars**.

AMECO variable `UVGD` is nominal GDP at current prices in each country's
**national currency**: USD for the United States, SEK for Sweden, DKK for
Denmark, and EUR for the euro-area countries in this dataset.

`OVGD` is AMECO's real GDP volume series at 2020 reference levels. Because its
reference-price level is 2020 in the current AMECO vintage, it is first rescaled
to the country's **2015 domestic price level** using the ratio

`UVGD_2015 / OVGD_2015`.

The resulting 2015-price GDP series is then converted from the country's
national currency into **PPS (Purchasing Power Standards)** using the country's
GDP PPP for **2015 only**, `KNP_2015`.

Thus, for every year t,

`Y_t^(constant 2015 PPS) = OVGD_t × (UVGD_2015 / OVGD_2015) / KNP_2015`.

Equivalently, define the country-specific fixed conversion factor

`F = (UVGD_2015 / OVGD_2015) / KNP_2015`.

Then

`Y_t^(constant 2015 PPS) = F × OVGD_t`.

**The factor F is fixed over the entire time series. There is no annual
revaluation using each year's PPP.** In particular, we do *not* compute
`UVGD_t / KNP_t`. Changes over time in GDP per capita relative to the United
States therefore reflect real GDP-volume growth and population growth, rather
than movements in annually updated PPP conversion rates.

PPS should not be interpreted literally as US dollars. It is a common
purchasing-power unit. The United States therefore also has a PPP conversion
factor different from one.

## PPP adjustment relative to market exchange rates

To show the economic significance of the PPP conversion, the table below
compares each country's 2015 PPP valuation with valuation at the average 2015
market exchange rate against the US dollar.

The reported **PPP adjustment factor** answers the following question:

> By what factor is the country's GDP level relative to the United States
> changed when 2015 PPPs are used instead of 2015 market exchange rates?

It is calculated as

`PPP adjustment factor_i = (E_i / KNP_i) / (E_US / KNP_US)`,

where `E_i` is the average 2015 market exchange rate in national-currency units
per USD and `KNP_i` is the 2015 GDP PPP in national-currency units per PPS.

A factor above 1 means that PPP conversion raises the country's GDP level
relative to the United States compared with conversion at market exchange
rates. A factor below 1 means that PPP conversion lowers it.

| Country | National currency | PPP adjustment factor |
|---|---|---:|
| United States | USD | 1.000 |
| Germany | EUR | 1.158 |
| France | EUR | 1.115 |
| Italy | EUR | 1.220 |
| Sweden | SEK | 0.952 |
| Denmark | DKK | 0.920 |
| Finland | EUR | 0.993 |
| Netherlands | EUR | 1.113 |
| Belgium | EUR | 1.127 |
| Spain | EUR | 1.356 |
| Austria | EUR | 1.128 |

For example, the factor 1.158 for Germany means that using 2015 PPPs rather
than the 2015 market exchange rate raises Germany's measured GDP level relative
to the United States by about 15.8 percent. For Sweden, the factor 0.952 means
that the PPP valuation is about 4.8 percent lower relative to the United States
than valuation at the average 2015 market exchange rate.

The market exchange rates used are annual 2015 averages. For the euro-area
countries, the 2015 average was USD 1.1095 per EUR. For Sweden and Denmark,
the corresponding annual average EUR exchange rates were combined with the
USD/EUR rate to obtain SEK/USD and DKK/USD rates.

## Other AMECO variables

- `NPTD`: total population (National Accounts)
- `NPAN1`: population aged 15–74
- `NETN`: employment, persons, total economy
- `NLHT`: total annual hours worked, total economy
- `OVGD`: real GDP volume series
- `UVGD`: nominal GDP at current prices, national currency
- `KNP`: GDP purchasing-power parity, national-currency units per PPS

For Sweden, AMECO's population aged 15–74 series ends after 2021 in the June
2026 vintage. From 2022 onward, A is supplemented with Eurostat `demo_pjan`,
summing single ages 15 through 74 for both sexes.

## Sources

- AMECO database, European Commission:
  https://economy-finance.ec.europa.eu/economic-research-and-databases/economic-databases/ameco-database_en
- Eurostat `demo_pjan`:
  https://ec.europa.eu/eurostat/databrowser/view/demo_pjan/default/table
- Banque de France Eco Notepad:
  https://www.banque-france.fr/en/publications-and-statistics/publications/revisiting-european-performance-gap-vis-vis-united-states

## Notes for EC2211 Course Assistant

Distinguish clearly between levels and US-relative indices. The decomposition is
multiplicative. Do not describe the five terms as additive contributions.

When discussing the GDP levels, describe them as **constant 2015 PPS**, not
current USD and not current PPS. Do not introduce annual PPP revaluation into
the series.

Values for 2025 may include AMECO estimates/forecasts and should not
automatically be treated as realised historical observations.
