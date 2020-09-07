# Master-Thesis
## Characterizing Sender Policy Framework Configurations at Scale
The code which has been used during my Master Thesis contains of two files:
1. Generate-Data.ipynb
2. Analysis.ipynb

The Generate-Data.ipynb file contains in the beginning all the functions to generate the Dataframes and after the "Loading Data & Creating Columns" section some sample code is given to generate the Dataframes.

The Analysis.ipynb contains the functions to analyse the Dataframes generated by Generate-Data.ipynb files.

The structure of how the files are stored on the HDFS server is as follows:

### {folder}/source={source}/data={data}/year={year}/month={month}/day={day}

An example is: 
### results/source=com/data=verify-all/year=2020/month=05/day=01

The only exception is the 'include-depth' Dataframe. The corresponding path contains a 'depth' variable at the end.

E.g.: 
### {folder}/source={source}/data={data}/year={year}/month={month}/day={day}/depth={depth}
