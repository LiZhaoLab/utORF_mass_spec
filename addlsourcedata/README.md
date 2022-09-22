### Additional Source Data

Contains various intermediates used for further work, or to reduce computation time.

| Filename                                    | contents                                                |
|---------------------------------------------|-------------------------------------------------------- |
| `LCA_factors_coded.csv`                     | from `LCA_data_preparation`; coded categ. vars. for LCA |
| `LCA_factors_indexed.pd.pic.gz`             | as above, but retaining index;                          |
| `LCA_factors_original.csv`                  | as above, but retaining original data values for all    |
| `Dmel_MS_LCA_5class_revised.RDS.bz2`        | from `LCA_call`; R object holding final fitted LCA model|
|`LCA_posterior_classes_revised.pandas.pic.gz`| from `LCA_call`; modal posterior class assignments      |
| `LCA_posterior_data_revised.pandas.pic.gz`  | from `LCA_call`; data values, indexed by class          |
| `elife-15.denovo_superstrict.pd.pic.gz`     | from `denovo_calls`; table of denovo origin calls       |