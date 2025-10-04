# Replication data for Age-related vulnerability greatly amplifies the risk of uncompensable heat
This repository contains the dataset and Jupyter Notebooks that can be used to reproduce all figures in the paper "***Age-related vulnerability greatly amplifies the risk of uncompensable heat***" by Kong et al. (2025). There are two folders:

- **./Jupyternotebook**: Jupyter Notebooks for reproducing figures in "Age-related vulnerability greatly amplifies the risk of uncompensable heat" by Kong et al.


- **./data**: dataset needed for running Jupyter notebooks including the following:

  - `Annual_uncompensable_heat_hours.nc`
    Annal number of hours exceeding the heat compensability limits for three age groups and 16 CMIP6 climate models under 1-4°C global warming

  - `Country_level_exposed_pop_num.nc`
    The number of young, middle-aged, and old population exposed to at least 180 hours of uncompensable heat stress annually in each individual country; for 15 CMIP6 climate models under 3°C warming

  - `Country_level_tot_pop_num.nc`
    Total number of young, middle-aged, and old population in each individual country; for 15 CMIP6 climate models under 3°C warming
    
  - `Global_exposed_population_by_age_groups.nc`
    Global number of young (15-34), middle-aged (35-64) and elderly population exposed to 180 and 540 hours of uncompensable heat annually, for 15 CMIP6 climate models under 1-4°C warming relative to preindustrial. Assuming 6 hours of threshold exceedance per day, 180 and 540 hours correspond to a month and a season.

  - `Global_exposed_population_by_age_groups_yong_limits.nc`
    Global number of young (15-34), middle-aged (35-64) and elderly population exposed to 180 and 540 hours of uncompensable heat (defined by young adult thresholds only) annually, for 15 CMIP6 climate models under 1-4°C warming relative to preindustrial. Assuming 6 hours of threshold exceedance per day, 180 and 540 hours correspond to a month and a season.

  - `Global_population_by_age_groups.nc`
    Global total population of young (15-34), middle-aged (35-64) and elderly adults (65 and older), for 15 CMIP6 climate models under 1-4°C warming relative to preindustrial

  - `Hourly_probability_of_threshold_exceedance.nc`
    Hourly probability of exceeding heat compensability limits for three age group, at 8 major cities, under 1.5, 2, 3, and 4°C warming relative to the preindustrial period


  - `limits_young.xlsx`; `limits_middle_aged.xlsx`; `limits_old.xlsx`
    Heat compensability limits experimental data for young (18-34), middle-aged (35-64) and old (65 and older) adults.

  - `pip3.0.xlsx`; `pip4.2.xlsx`; `pip8.3.xlsx`
    Country-level poverty rate dataset based on three poverty criteria: $3.0, $4.2, and $8.3 per day in 2021 Purchasing Power Parities
