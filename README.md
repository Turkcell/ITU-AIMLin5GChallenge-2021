# ITU-AIMLin5GChallenge-2021

# Background

Cloud, rain, snow, and other weather-related phenomena affects the performance of radio links. This is especially applicable to backhaul links operating at GHz frequencies. A generic regional weather forecast data is available which lists expected conditions and coarse temperatures along with actual –precise– realizations.

Adding to the complexity are the spatial nature of the data (regions of weather data and RLF needs to be aligned) as well as the time sync needed to correlate various occurrences. Over a period of time, we have compiled and anonymised region-wise data which corresponds to weather forecasts, and RLFs derived from our networks.

# Problems

Given the region-wise, historical data sets derived from our networks, with weather forecast as well as radio link (RL) performance (for a given frequency band), predict the RLFs. 

# Academia
This dataset is not only limited for Radio Link Failure. This data gives the opportunity for researchers to use live network data to define new problems or improve their works.

## Citation
The dataset is introduced in the following article:
https://www.sciencedirect.com/science/article/pii/S004579062200053

In this article, you can follow the state-of-the-art models' results and the novel proposed model to predict radio link failure. Please use the following BibTeX:

```
@article{AKTAS2022107742,
title = {Towards 5G and beyond radio link diagnosis: Radio link failure prediction by using historical weather, link parameters},
journal = {Computers & Electrical Engineering},
volume = {99},
pages = {107742},
year = {2022},
issn = {0045-7906},
doi = {https://doi.org/10.1016/j.compeleceng.2022.107742},
url = {https://www.sciencedirect.com/science/article/pii/S0045790622000532},
author = {Semih Aktaş and Hande Alemdar and Salih Ergüt},
}
```
