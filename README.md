# NAMCS-pain-and-chronic-conditions
Code used for and referenced in my Honors Thesis at Brigham Young University.

All pre-processing on the NAMCS data has been done, and interested parties can move immediately to the data_exploration and ML_methods folders.
However, if you want to start with the base data files for whatever reason, they will have to be downloaded.
The CDC has all data files available at https://www.cdc.gov/nchs/ahcd/datasets_documentation_related.htm.
Once downloaded, the data files will have to be processed using the files found in the 'processing' folder before being used by the data_exploration and ML_methods folders.

The files in the processing folder should be run in the following order:
1. 2016_translation
  - Note that this will translate the ICD-10 codes in the 2016 data file to ICD-9 codes, to match all other years. Any years from 2016 onwards should have the same script run on them.
2. process
3. chronic database create

For further explanation of the results drawn from this code, please see "An Analysis of Opiate Prescription for Chronic Degenerative Disease and Other Pain Syndromes" by Catherine Sawyer, an Honors Thesis at Brigham Young University.
