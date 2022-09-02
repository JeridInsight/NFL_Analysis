# NFL_Analysis
 Files for NFL data analysis...
 
 The files work like this:
 
 The nfl_pass_rush_receive_raw_data.csv file is the raw data file.  The NFL_2022_Data_Prep.ipynb is the Jupyter notebook that processes that raw file.  It cleanses the data, transforms it and reshapes it into a dimensional model to be used in Power BI. The NFL_2022_Data.xlsx file is the output of that Jupyter notebook and it is what gets ingested into Power BI.  The .pbit file (Template file) is parameterized and prompts you for the location (path) of the NFL_2022_Data.xlsx file on your local machine (wherever you saved it to).  Paste the path of the file into the prompt and the .pbit should load all the data into PBI. 
 
 If you want to work with the Jupyter notebook and you are a beginner with Python, I would suggest that you install Anaconda (https://www.anaconda.com/products/distribution) and from there open the Anaconda Navigator and utilize JupyterLab.  This should be the easist way for a newb.  I know because this is how I do it. ; ) 
