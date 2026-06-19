# CSV Data UBS

This repository stores personally measured EMG hand-gesture data collected in a
research-lab setting. It is intended as a small data repository for experiments
with hand gesture classification.

## Data Source

- Measurement source: personally collected lab data.
- Sensor type: EMG-style multi-channel measurements.
- Format: CSV.
- Public-use note: this repository documents the dataset structure, but users
  should contact the owner before using the data in external research or
  redistribution.

## Label Meaning

| Label | Meaning |
| --- | --- |
| `0` | All fingers folded |
| `5` | All fingers fully extended |
| `12` | 4th and 5th fingers extended |
| `34` | 2nd and 3rd fingers extended |

## Files

| Path | Rows | Columns | Description |
| --- | ---: | ---: | --- |
| `CSV/usedata/0/0_40.csv` | 41 | 8 | Class `0` sample |
| `CSV/usedata/5/5_40.csv` | 41 | 8 | Class `5` sample |
| `CSV/usedata/12/5_40.csv` | 41 | 8 | Class `12` sample |
| `CSV/usedata/34/34_40.csv` | 41 | 8 | Class `34` sample |
| `CSV/dataprogram.ipynb` | - | - | Notebook used to collect or reorganize CSV files |

## Recommended Citation / Attribution

If the data is used in a report, note that it was personally measured by the
repository owner in a lab environment. Add measurement date, sensor model and
protocol details here when they are available.

## Next Cleanup

1. Add sensor model and sampling rate.
2. Add electrode placement or measurement protocol.
3. Rename `CSV/usedata/12/5_40.csv` if the filename should match label `12`.
4. Add a short example notebook that loads all classes into one dataset.
