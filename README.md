# Example data for MISA
These are the example datasets provided for [MISA].

Generating scripts are also included for some examples and may require `@gsd` and/or `@gsm` classes defined in [MISA].

[MISA]: https://github.com/rsilva8/MISA

## Files
- `MISA-data.zip`: contains datasets organized into 2 subfolders:
    - `Sgt`: synthetic sources and generating code.
    - `real_data_features`: features from real data for hybrid examples.
        - structural MRI maps taken from [pub1]:

        [pub1]: https://doi.org/10.3389/fninf.2012.00010

        J. Segall, E. Allen, R. Jung, E. Erhardt, S. Arja, K. Kiehl, and V. Calhoun, “Correspondence between structure and function in the human brain at rest,” Front Neuroinform, vol. 6, p. 10, 2012.

        - functional MRI maps taken from [pub2]:

        [pub2]: https://doi.org/10.3389/fnsys.2011.00002

        E. A. Allen, E. B. Erhardt, E. Damaraju, W. Gruner, J. M. Segall, R. Silva, M. Havlicek, S. Rachakonda, J. Fries, R. Kalyanam, and et al., “A baseline for the multivariate comparison of resting-state networks,” Front Syst Neurosci, vol. 5, 2011.

        - connectivity parcellation maps based on fractional anisotropy-based diffusion MRI taken from [pub3]:

        [pub3]: https://doi.org/10.1002/hbm.22945

        L. Wu, V. D. Calhoun, R. E. Jung, and A. Caprihan, “Connectivity-based whole brain dual parcellation by group ICA reveals tract structures and decreased connectivity in schizophrenia,” Hum Brain Mapp, vol. 36, no. 11, pp. 4681–4701, 2015.

## Usage
```
git clone git@github.com:rsilva8/MISA-data.git MISA-data
cd MISA-data
unzip MISA-data.zip
```

## License
