# HebrewCopula
Contains Python and R scripts with analyses of the copula in Biblical Hebrew

copula_data_perpare_bib.ipynb is a script for preprocessing the biblical data. It uses the Python library [Text-
Fabric](https://github.com/Dans-labs/text-fabric/wiki). It extracts data from the ETCBC database, version BHSA c.

copula_data_prepare_xbib.ipynb preprocesses the extrabiblical data. It needs the extrabiblical dataset. This contains presently the Dead Sea Scrolls 1QM and 1QS and some Hebrew inscriptions.

The two files are nearly identical, but there are slight differences in the data format of the biblical and extrabiblical data, so I have decided to keep the scripts separated.

The files hyh_nom_biblical.csv and hyh_nom_extrabiblical.csv are the output produced by the Python scripts.

The file copula_analysis_R.txt imports the output of the two Python files into R. There some further preprocessing is done, after which the resulting dataset is analyzed.
