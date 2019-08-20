STEPS TO RUNNING THE DATA CLEANING AND MACHINE LEARNING:

CLEAN DATA FOR 2010 AND 2015 IS ALREADY AVAILABLE.

To run ML on other years:

1. Separate a year from mldata_clean.csv.
	Run ETL_Concat_2010.ipynb
	Run ETL_Mega_2010.ipynb
	Read in POP_2000_2018.csv
	Add year column
	Result: Dataframe with all feature EXCEPT Food Desert feature

2. Apply ML Formula to features
	

3. Process Machine Learning
	Run Scikit_Pred_G_Etab.ipynb
	or one of the other Scikits