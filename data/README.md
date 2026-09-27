# Data documentation

## Included file

`raw/LSOA_data.csv` is the analysis-ready dataset used by the project
notebook. It contains one row for each 2021 Lower Layer Super Output Area
(LSOA) in England.

| Property | Value |
|---|---:|
| Rows | 33,755 |
| Columns | 23 |
| Population represented | 56,490,091 |
| Missing cells | 0 |
| Duplicated LSOA codes | 0 |
| Rows where age-band counts differ from `Total` | 0 |

## Variables

- `LSOAName`, `LSOACode`: neighbourhood name and identifier.
- `PartOfName`, `PartOfCode`: containing local-authority geography.
- `Total`: usual residents recorded for the LSOA.
- `Age4Under` through `Age85Over`: resident counts across 18 five-year age
  bands, with an open-ended final band for residents aged 85 and over.

## Provenance

The file is an adapted extract derived from **Office for National Statistics
Census 2021 table TS007A: Age by five-year age bands**, obtained through
[Nomis](https://www.nomisweb.co.uk/datasets/c2021ts007a).

Relative to the source release, the prepared file:

- retains English LSOAs only;
- uses shortened, space-free column names; and
- includes parent-geography codes and names.

The project does not require the larger original download or the optional
geographic boundary file.

## Integrity check

The included analysis-ready file has the following SHA-256 checksum:

```text
54c4e282c0b56e1e2f1c0e5e0364487c6b7ca5702f2d9ffb5900b4c51c50094f
```

## Statistical disclosure control

Census 2021 outputs apply statistical disclosure controls. These include
record swapping and small perturbations to some counts, so minor differences
can occur between published tables with different breakdowns.

## Licence and attribution

Standard Census 2021 outputs are available under the
[Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
When reusing this adapted file, retain the following attribution:

> ONS: Adapted from data from the Office for National Statistics licensed
> under the Open Government Licence v3.0.

See [ATTRIBUTION.md](ATTRIBUTION.md) for the repository attribution notice.
