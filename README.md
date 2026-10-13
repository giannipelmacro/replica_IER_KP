# Replication package

**Real Activity and Uncertainty Shocks: The Long and the Short of It**
Mathias Krogh and Giovanni Pellegrino, *International Economic Review*, forthcoming.

This repository contains the MATLAB/Dynare codes and data that reproduce the figures and results of the paper and its online appendix.

## How to use it

Download `replica_IER_KP.zip`: click on the file above, then on the download button. Unzip it and start from `readme.txt`, which lists the script behind each figure.

## Contents

| Folder | What it does | Paper |
|---|---|---|
| `VIXdata` | Constructs the VIX term structure, including the new two-year VIX | Section 3, Appendix A |
| `VAR` | SVAR identification of short- and long-term uncertainty shocks | Section 4, Appendices C–E |
| `LP` | Local projections, using the SVAR shocks as instruments | Section 4.2, Appendix F |
| `DSGE` | DSGE model with time-to-build in investment | Section 5, Appendices G–H |

## Data

The constructed VIX series and all other data needed to reproduce the results are included. The raw S&P 500 option data, from OptionMetrics through WRDS, are proprietary and cannot be redistributed; they are available to WRDS subscribers. The codes that build the VIX term structure from these raw data are included (see `VIXdata/_Read-me.docx`).

## Software

MATLAB R2021b and Dynare 4.4.3.

## Contact

Mathias Krogh (mathias.s.krogh@gmail.com) and Giovanni Pellegrino (giovanni.pellegrino@unipd.it)
