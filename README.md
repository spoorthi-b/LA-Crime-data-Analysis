# LA Crime Data Analysis and Visualization:

## About the Project
In this project, our objective is to analyze the crime data containing various crimes that occurred in Los Angeles for a period of time. We want to live in a world that is ideally safe and free of crimes. Unfortunately, that is not the case in the real world. <br />

While such crimes are out of our control, We can use the data provided by the LAPD to aid the authorities by identifying the crime hotspots in Los Angeles and studying the patterns involved in these crimes, such as the type of neighborhood where these crimes occur. Through this analysis, we identify the patterns behind these crimes and go into further detail by pinpointing the frequent type of crimes, identifying the top most dangerous areas, and
specifying times with higher crime incidents. We then use clustering algorithms to highlight the areas with the highest crime rates and visualize the data in an informative manner. <br />

There are many Clustering algorithms to choose from, and no single best clustering algorithm for all cases. We will KMeans, Bisecting KMeans and GMM clustering algorithms to determine the most effective. We will also use Big Data tools such as pySpark to preprocess the data and Spark SQL for OLAP, and these tools will enable us to process complex data from large datasets quickly and efficiently.


## Installation Requirements:
● Python3 <br />
● Jupyter Notebook <br />
● Java <br />
● Spark <br />
● MySQL <br />
● Python Libraries: <br />
  &emsp;○ PySpark <br />
  &emsp;○ Pandas <br />
  &emsp;○ Matplotlib <br />
  &emsp;○ Seaborn <br />
  &emsp;○ Folium <br />
  &emsp;○ Numpy <br />
  &emsp;○ Geopandas <br />
  &emsp;○ Shapely <br />
Note: Our project is completely executed in a python 3 jupyter notebook environment. The initial requirements are listed above and then all the python libraries need to be installed in  the python console using pip or pip3.

## Dataset:
The dataset has more than a million rows that delineate the crime incident. It has 28 attributes that contain numerical, text, and date-time data. <br /> You can download the dataset for the project from the link provided in 'dataset_link.txt' file. Please place the downloaded csv file in src folder.

## Instructions:
● Please unzip the F22-CS226-Code-13.tar.gz file and you will be able to find four ‘.ipynb’ in folder 'src'. <br />
● Please run the Jupyter Notebooks in the following order: <br />
We have attached both html and ipynb files for our project, kindly refer to our html files only if you cannot run the ipynb files, as it preserves the visualization and does not require any installation. <br />
<br />
 
1. OLAP: <br />
  &emsp;a. OLAP_AGE_ANALYSIS.ipynb: This file contains Age based Analysis, Age classification, Multi-level query on Age subset vs Crime Area. <br />
  &emsp;b. OLAP_WHEN_WHERE_HOW.ipynb: This file contains the code to preprocess and visualize the dataset and answers questions pertaining to crime across different time periods, weapons of choice on various premises, and typical crimes inflicted across various victim descent. <br />
  &emsp;c. OLAP_VICTIM_SEX_ANALYSIS.ipynb: This file contains the code to preprocess and visualize the dataset based on Victim’s Gender, Ethnicity, and Locality. <br />
  &emsp;d. OLAP_AREA.ipynb: This file contains code to preprocess and visualize crime dataset based on the area the time took place. <br />
  
2. CLUSTERING ALGORITHM: <br />
&emsp;CLUSTERING_ALGO.ipynb: This file contains code for implementing three clustering models using PySpark and Pandas. Please run all cells from the beginning.
