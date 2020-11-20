# Cleaning and analysing data gathererd from driving in VR

```/data-cleanup```  
Contains script for merging all separate .csv files into a single one, which makes it easier to import with Python  
It also remove rows for each separate .csv where SoC < 0 before merging (bug in the simulaor which stores false data after SoC < 0)  

```/juptyer-notebooks```   
Contains all jupyter notebooks for analysing the data  
If you want to run these you have to install juyter notebook, I think it's easiest to use Anaconda: https://anaconda.org/

```/raw-data```  
Contains all the individual driving sessions in .csv format

```/figures```  
Save useful figures here
