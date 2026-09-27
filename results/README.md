# Results summary

This file summarises the principal outputs from the
[analysis notebook](../notebooks/england_lsoa_demographic_analysis.ipynb).

## Dataset

- 33,755 English Lower Layer Super Output Areas
- 56,490,091 residents
- 18 five-year age bands from ages 0-4 through 85+
- No missing cells or duplicated LSOA codes
- Age-band counts match the recorded total in every row

## National age profile

The 30-to-34 group is the largest individual five-year age band, representing
approximately 7.0% of the analysed population. Several working-age groups have
similar shares, while the oldest bands contain smaller proportions.

## Selected neighbourhood profiles

| LSOA | Younger share (0-19) | Older share (65+) | Estimated median age |
|---|---:|---:|---:|
| Bury 026E | 49.7% | 7.3% | 20.39 years |
| Birmingham 014E | 23.3% | 22.7% | 40.15 years |
| Dorset 024A | 9.1% | 54.6% | 67.67 years |

These examples demonstrate local variation but are not intended to represent
all neighbourhoods within their wider authorities.

## Median-age estimates

- Grouped national median-age estimate: **40.43 years**
- Median of the 33,755 LSOA median-age estimates: **41.46 years**

The first statistic weights each resident equally. The second gives each LSOA
equal weight regardless of its population.

| Parent area type | LSOAs | Median estimated age |
|---|---:|---:|
| London borough | 4,994 | 36.15 years |
| Metropolitan district | 7,335 | 39.97 years |
| Unitary authority | 8,827 | 42.28 years |
| Non-metropolitan district | 12,599 | 45.05 years |

## Exploratory demographic profiles

Quartile thresholds were used to label LSOAs with relatively unusual younger,
older or working-age-dominant population shares.

- 23.7% of London-borough LSOAs were labelled **Younger**.
- 23.5% of non-metropolitan-district LSOAs were labelled **Older**.
- 13.3% of London-borough LSOAs were labelled **Working-age dominant**.

These labels are dataset-dependent heuristics rather than official demographic
classifications.

## Interpretation limits

- The dataset describes Census Day, 21 March 2021, and does not measure change
  over time.
- Median age is estimated from grouped counts rather than individual ages.
- The analysis is descriptive and does not explain the causes of geographic
  differences.
- Census statistical disclosure controls can create minor differences between
  published tables with different breakdowns.
