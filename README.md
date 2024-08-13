This is a demo for Question 3c 
Assuming i have a collection of CSV files containing sales data from different regions, along with some related metadata and documentation.
I uploaded a file with directory structure with breakdown as follows:
data/: Contains all data files.

raw/: Holds the raw, unprocessed data files. This is the original data as received from the source.
processed/: Contains processed data files, such as aggregated or cleaned datasets.
metadata/: Stores metadata files related to each data source, describing the structure and meaning of the data.
archive/: Used for backups of the raw and processed datasets, which might be zipped or stored in a compressed format.
scripts/: Contains all scripts used for data processing, analysis, and visualization.

data_cleaning.py: Python script for cleaning the raw data.
data_analysis.py: Python script for analyzing the processed data.
visualization.ipynb: Jupyter notebook for creating visualizations from the data.
docs/: Contains documentation related to the dataset and the project.

README.md: Overview of the project, setup instructions, and usage guide.
data_description.md: Detailed description of the dataset, including variables, units, and sources.
analysis_report.md: Report summarizing the analysis results.
.gitignore: Specifies files and directories that Git should ignore, such as large datasets not meant for version control, environment files, or temporary files.

LICENSE: Contains the licensing information for the project, defining how the data and code can be used by others.
