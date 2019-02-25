# opendoors
Jupyter notebook to parse data for Open Doors reporting

In order to run this notebook, you will need to have Python and Jupyter notebooks installed on your computer. The easiest way to do this is to download and install the [Anaconda Python distribution](https://www.anaconda.com/distribution/). This will include all of the packages and tools needed to work with Jupyter Notebooks and other python tricks. Administrator credentials are not required to install this.  
  
## What's in here?
- **OpenDoors2018.ipynb**: The Jupyter notebook that contains the python code used to parse the following data sources
- **sampleData.csv**: The main data source. This table was created by the univeristy's reporting system using student data. Your univeristy will have different data. The scripts in the notebook are set up to parse the columns in this file based on their names. If your data source is labeled differently, you can just change the column names and most of the script should work.  
- **STVMAJR.csv**: This table contains the major codes used in our univeristy's student information system and the corresponding CIP codes. If your base report has cip code data, you can comment out the mergedDF dataframe creation and run the last field of study cell off of your base dataframe. 

