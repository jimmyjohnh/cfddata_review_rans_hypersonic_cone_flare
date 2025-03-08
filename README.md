# CFD data for Review on RANS for hypersonic cone flare
This repository contains the CFD simulation data obtained by various participants in the simulation of hypersonic large cone-flare geometries.
It is associated with the Physics of Fluids Journal Paper:
```
Hoste, JJOE; Gibbons, N; Ecker, T; Amato, C; Knight, D; Sattarov, A; Thiry, O; Hickey, JP; Hizir, FE; Kokturk, T; Castelino, N; Viti, V; Roldan, MA; Qiang, S; Coder, JG; Baurle, RA and White, JA; "A review of Reynolds-Averaged Navier-Stokes modeling for hypersonic large cone-flares", Physics of Fluids, 37(2), 2025, https://doi.org/10.1063/5.0246552
```


## Explanation of data
In the folder `cfd_data`, specific run data is provided for each case `Case1_6_42` and `Case2_7_40`. An example tree structure is provided below for `Case1_6_42` with subfolders for each participant and the wall - pressure and - heat flux data. The `.csv` filenames contain the turbulence model used (see paper for the exact details).

In addition, the data which is tabulated in the manuscript for each run is also provided as `{RUNXX}_integrated_values.csv` and `{RUNXX}_separation_peaks.csv`. The first naming convention refers to integrated quantities. The second naming contains information related to specific scalar values for peak and locations.

The experimental data is provided in the folder `experimental_data`.
```
└── run4
    ├── ansys_aselsan
    │   ├── run4_ansys_aselsan_wallHeatFlux_SA1T.csv
    │   ├── run4_ansys_aselsan_wallHeatFlux_SA2T.csv
    │   ├── run4_ansys_aselsan_wallHeatFlux_SST1T.csv
    │   ├── run4_ansys_aselsan_wallHeatFlux_SST2T.csv
    │   ├── run4_ansys_aselsan_wallP_SA1T.csv
    │   ├── run4_ansys_aselsan_wallP_SA2T.csv
    │   ├── run4_ansys_aselsan_wallP_SST1T.csv
    │   └── run4_ansys_aselsan_wallP_SST2T.csv
    ├── cadence
    │   ├── run4_cadence_wallHeatFlux_SSC-EARSM.csv
    │   ├── run4_cadence_wallHeatFlux_SST-a10355.csv
    │   ├── run4_cadence_wallP_SSC-EARSM.csv
    │   └── run4_cadence_wallP_SST-a10355.csv
    ├── eilmer
    │   ├── run4_eilmer_wallHeatFlux_wilcox2006-klimV.csv
    │   └── run4_eilmer_wallP_wilcox2006-klimV.csv
    ├── overflow
    │   ├── run4_overflow_wallHeatFlux_SST.csv
    │   └── run4_overflow_wallP_SST.csv
    ├── run4_integrated_values.csv
    ├── run4_separation_peaks.csv
    ├── starccm
    │   ├── run4_starccm_wallHeatFlux_SST.csv
    │   └── run4_starccm_wallP_SST.csv
    ├── SU2
    │   ├── run4_SU2_wallHeatFlux_SST01mm.csv
    │   ├── run4_SU2_wallHeatFlux_SST05mm.csv
    │   ├── run4_SU2_wallHeatFlux_SST125mm.csv
    │   ├── run4_SU2_wallHeatFlux_SST260mm.csv
    │   ├── run4_SU2_wallP_SST01mm.csv
    │   ├── run4_SU2_wallP_SST05mm.csv
    │   ├── run4_SU2_wallP_SST125mm.csv
    │   └── run4_SU2_wallP_SST260mm.csv
    └── vulcan
        ├── run4_vulcan_wallHeatFlux_SA-noft2.csv
        ├── run4_vulcan_wallHeatFlux_SA-noft2-QCR-V.csv
        ├── run4_vulcan_wallHeatFlux_SST.csv
        ├── run4_vulcan_wallHeatFlux_SST-KL.csv
        ├── run4_vulcan_wallHeatFlux_SST-V.csv
        ├── run4_vulcan_wallHeatFlux_SST-Vm.csv
        ├── run4_vulcan_wallP_SA-noft2.csv
        ├── run4_vulcan_wallP_SA-noft2-QCR-V.csv
        ├── run4_vulcan_wallP_SST.csv
        ├── run4_vulcan_wallP_SST-KL.csv
        ├── run4_vulcan_wallP_SST-V.csv
        └── run4_vulcan_wallP_SST-Vm.csv

```
