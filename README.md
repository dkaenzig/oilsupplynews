# Oil Supply News Shocks: Data Vintages

This repository provides data vintages for the **oil supply news shocks** introduced in:

Känzig, Diego R. (2021). *The Macroeconomic Effects of Oil Supply News: Evidence from OPEC Announcements.*  
American Economic Review.  
Paper: https://www.aeaweb.org/articles?id=10.1257/aer.20190964

The repository contains Excel files with:

- **Daily oil supply surprises**
- **Monthly oil supply surprises**
- **Monthly oil supply news shocks**, extracted from the VAR in the paper

## File Naming Convention

Files follow the format:

`oilSupplyNewsShocks_yyyyMmm.xlsx`

where

- `yyyy` = year of the data vintage  
- `mm` = month of the data vintage

The vintage corresponds to the **last observation available in the dataset** at the time the file was created.

Each Excel file contains four worksheets:

`Daily`: Daily oil supply surprises for the full available sample.

`Monthly`: Monthly oil supply surprises and the **oil supply news shock** constructed from the VAR.

`Daily (pre-Covid)`: Daily oil supply surprises, restricted to the sample ending before the Covid-19 pandemic.

`Monthly (pre-Covid)`: Monthly oil supply surprises and the VAR-based oil supply news shock for the pre-Covid sample.

## VAR Dataset

The repository also includes the dataset used in the **baseline VAR** specification:

`VARdata.xlsx`

This file contains data on the WTI oil price, world oil production, world oil inventories, world industrial production, U.S. industrial production and the U.S. CPI. For more details, see Appendix B.2.

## Update Frequency

The dataset is updated approximately **every six months**.

Due to publication lags in some of the underlying macroeconomic data series, updates typically become available with a delay of **4–5 months**.

## License

The data are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt the data provided appropriate credit is given. If you use these data, please cite the following paper:

Känzig, Diego R. (2021).  
*The Macroeconomic Effects of Oil Supply News: Evidence from OPEC Announcements.*  
American Economic Review.  
https://doi.org/10.1257/aer.20190964

```bibtex
@article{kanzig2021oilsupplynews,
  title   = {The Macroeconomic Effects of Oil Supply News: Evidence from OPEC Announcements},
  author  = {Känzig, Diego},
  journal = {American Economic Review},
  year    = {2021},
  volume  = {111},
  number  = {4},
  pages   = {1092--1125},
  doi     = {10.1257/aer.20190964}
}
```

## Contact

Diego Känzig  
Northwestern University  
Email: dkaenzig@northwestern.edu
