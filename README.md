# SIOC 251: Radiation in the Atmosphere

**Author:** Willa Tobin
**Term:** Spring 2026

## Directory Structure

```
sioc251_radiative_transfer/
├── HW0_prism_dispersion/           # Homework 0: Prism dispersion
│   ├── model.ipynb                 # Ray tracing model for light through a prism
│   ├── SIOC_251_Homework_0.pdf     # Assignment description
│   └── figures/
│       ├── light_through_prism.png
│       └── test_case.png
├── HW1_monte_carlo_extinction/     # Homework 1: Monte Carlo extinction model
│   ├── monte_carlo.ipynb           # Monte Carlo model of solar radiation in an absorbing atmosphere
│   ├── SIOC_251_Homework_1.pdf     # Assignment description
│   ├── data/
│   │   ├── 20230607_20230607_CCNY.lev20  # AERONET Level 2.0 AOD data (CCNY, 2023-06-07)
│   │   └── aeronet_chart.gif             # AERONET web chart for selected day
│   └── figures/
│       ├── IMG_5895.JPG                         # Photo of NYC smoke event (2023-06-07)
│       ├── test1_transmission_vs_theta.png
│       ├── test2_transmission_vs_tau.png
│       ├── q4_transmission_vs_depth.png
│       ├── q5_transmission_const_tau.png
│       ├── q5_transmission_const_theta.png
│       ├── aeronet_aod_and_sza.png
│       ├── part5_transmission_vs_temperature.png
│       └── part5_transmission_vs_norm_depth.png
├── HW2_longwave_model/             # Homework 2: Longwave radiative transfer model
│   ├── lw_model.ipynb              # Longwave radiative transfer model
│   └── SIOC_251_Homework_2.pdf     # Assignment description
├── HW3_monte_carlo_scattering_PartI/  # Homework 3: Monte Carlo scattering model
│   ├── scattering_model.ipynb         # Monte Carlo model with scattering (Parts 1–2)
│   ├── scattering_model_pt3.ipynb     # Monte Carlo scattering model (Part 3)
│   ├── SIOC_251_Homework_3.pdf        # Assignment description
│   └── figures/
│       ├── aerosol_cloud_layer_order.png
│       ├── albedo_mc_vs_analytical.png
│       ├── backscattering_fraction.png
│       ├── cirrus_cloud_transmission_fractions.png
│       ├── diffuse_transmittance_mc_vs_analytical.png
│       ├── diffuse_transmittance_vs_w_tau_theta.png
│       ├── extinction_events_vs_solar_zenith.png
│       ├── extinction_fraction_g_backscattering.png
│       ├── f_g_functional_relationship.png
│       ├── hg_phase_function_verification.png
│       ├── rayleigh_scattering_sky_blue_sunset.png
│       ├── sw_cre_vs_r_eff.png
│       ├── test_case1_absorption_vs_w.png
│       ├── test_case2_direct_transmittance.png
│       ├── variation_in_extinction_events.png
│       └── verification_cloud_top_height.png
├── HW4_two_stream_aerosol_DRE/     # Homework 4: Two-stream aerosol direct radiative effect
│   ├── two_stream_aerosol_DRE.ipynb  # Two-stream RT model for aerosol DRE
│   ├── SIOC_251_Homework_4.pdf       # Assignment description
│   ├── data/
│   │   ├── Fo.csv                    # Solar irradiance spectrum
│   │   ├── aerosol_properties.csv    # Aerosol optical properties
│   │   ├── ocean_reflectance.csv     # Ocean surface reflectance
│   │   └── reflect.csv              # Surface reflectance data
│   └── figures/
│       ├── aer_reflectance_transmittance.png
│       ├── aer_single_scatter_properties.png
│       ├── cre_atm_bar.png
│       ├── cre_sfc_bar.png
│       ├── cre_spectral.png
│       ├── cre_toa_bar.png
│       ├── dre_surface_albedo.png
│       ├── surface_reflectance_spectra.png
│       ├── surface_solar_flux.png
│       ├── test1_cloud_rt.png
│       ├── test2_surface_reflection.png
│       └── toa_dre_vs_tau.png
├── environment.yml
└── README.md
```
