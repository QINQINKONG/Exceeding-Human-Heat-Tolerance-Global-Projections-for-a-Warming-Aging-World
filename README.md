# Replication data for Exceeding Human Heat Tolerance: Global Projections for a Warming, Aging World
This repository contains the dataset and Jupyter Notebooks that can be used to reproduce all figures in the paper "***Exceeding Human Heat Tolerance: Global Projections for a Warming, Aging World***" by Kong et al. (2026). There are two folders:

- **./Jupyternotebook**: Jupyter Notebooks for reproducing figures in "Exceeding Human Heat Tolerance: Global Projections for a Warming, Aging World" by Kong et al.

- **./data**: dataset needed for running Jupyter notebooks including the following:

  - `Annual_uncompensable_heat_hours.nc`
    Annal number of hours exceeding heat compensability limits for three age groups at 1.5, 2, 3, and 4°C warming based on ensemble mean of 15 CMIP6 climate models.
  - `Annual_uncompensable_heat_hours_region_adjustment.nc`
    Same as above but based on regionally adjusted heat compensability thresholds to account for the effects of heat acclimatization.
  - `Annual_uncompensable_heat_hours_modeling_approach.nc`
    Same as above but based on an alternative approach that models heat compensability thresholds as continuous functions of age and ambient temperature.
  - `Annual_personxhours_of_uncompensable_heat.nc`
    Annual accumulated person-hours exceeding heat compensability limits at 1.5, 2, 3, and 4°C of global warming relative to the preindustrial period.
  - `climatological_annual_mean_temperature.nc`
    Annual average temperature during 1996–2025.
  - `ERA5_land_mask.nc`
    Land mask file based on the grid spacing of ERA5 reanalysis dataset.
  - `Country_level_exposed_pop_num.nc`
    The number of young, middle-aged, and old population exposed to at least 180 hours of uncompensable heat stress annually in each individual country; for 15 CMIP6 climate models under 3°C warming
  - `Country_level_tot_pop_num.nc`
    Total number of young, middle-aged, and old population in each individual country; for 15 CMIP6 climate models under 3°C warming
  - `Global_exposed_population_by_age_groups.nc`
    Global number of young (15-34), middle-aged (35-64) and elderly population exposed to 180 and 540 hours of uncompensable heat annually, for 15 CMIP6 climate models under 1-4°C warming relative to preindustrial. Assuming 6 hours of threshold exceedance per day, 180 and 540 hours correspond to a month and a season.
  - `Global_exposed_population_by_age_groups_region_adjustment.nc`
    Same as above but based on regionally-adjusted heat compensability thresholds to account for the effects of heat acclimatization.
  - `Global_exposed_population_by_age_groups_modeling_approach.nc`
    Same as above but based on an alternative approach that models heat compensability thresholds as continuous functions of age and ambient temperature.
  - `Global_exposed_population_by_age_groups_yong_limits.nc`
    Global number of young (15-34), middle-aged (35-64) and elderly population exposed to 180 and 540 hours of uncompensable heat (defined by young adult thresholds only) annually, for 15 CMIP6 climate models under 1-4°C warming relative to preindustrial. Assuming 6 hours of threshold exceedance per day, 180 and 540 hours correspond to a month and a season.
  - `Global_population_by_age_groups.nc`
    Global total population of young (15-34), middle-aged (35-64) and elderly adults (65 and older), for 15 CMIP6 climate models under 1-4°C warming relative to preindustrial
  - `Global_population_by_age_groups_modeling_approach.nc`
    Same as above but based on an alternative approach that models heat compensability thresholds as continuous functions of age and ambient temperature.
  - `Hourly_probability_of_threshold_exceedance.nc`
    Hourly probability of exceeding heat compensability limits for three age group, at 8 major cities, under 1.5, 2, 3, and 4°C warming relative to the preindustrial period
  - `limits_young.xlsx`; `limits_middle_aged.xlsx`; `limits_old.xlsx`
    Heat compensability limits experimental data for young (18-34), middle-aged (35-64) and old (65 and older) adults.
  - `limits_all.xlsx`
    Heat compensability limits experimental data for all ages. This combined file will be used for modeling heat compensablity thresholds as continuous functions of ambient temperature and age.
    
  - `pip3.0.xlsx`; `pip4.2.xlsx`; `pip8.3.xlsx`
    Country-level poverty rate dataset based on three poverty criteria: $3.0, $4.2, and $8.3 per day in 2021 Purchasing Power Parities
