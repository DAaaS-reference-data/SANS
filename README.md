# Small Angle Neutron Scattering (SANS) Reference Data Set

This repository contains a Small Angle Neutron Scattering (SANS) data set taken on the LOQ time-of-flight (TOF) instrument at the ISIS Neutron and Muon Source (UK). This data set was part of an investigation into creating a new protein standard for protein small angle scattering (SAS), which is published in Biomedical Spectroscopy and Imaging **6** (2017) 123–134 (https://doi.org/10.3233/BSI-170167). The purpose of this data set is to act as a reference data set to test and validate Data Analysis as a Service (DAaaS) platforms, for example as part of the [EU ExPaNDS project](https://expands.eu/).

#### file information

The file [experimental_setup.txt](https://github.com/DAaaS-reference-data/SANS/blob/main/experimental_setup.txt) details the setup of the experiment, while [experimental_log.pdf](https://github.com/DAaaS-reference-data/SANS/blob/main/experimental_log.pdf) summarises some basic information about the individual experimental runs.

The raw data files are included in the [nexus_files](https://github.com/DAaaS-reference-data/SANS/tree/main/nexus_files) directory, with the reduced data located in the [original_reduced_data](https://github.com/DAaaS-reference-data/SANS/tree/main/original_reduced_data) directory and the mantid files used to run the reduction production present in [mantid-files](https://github.com/DAaaS-reference-data/SANS/tree/main/mantid-files).

A jupyter notebook ([ExPaNDS_reduction.ipynb](https://github.com/DAaaS-reference-data/SANS/blob/main/ExPaNDS_reduction.ipynb)) is provided as an example of how these files can be utilised to reduce the raw data and reproduce the published data.