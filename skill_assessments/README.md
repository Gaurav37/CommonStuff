1. First skill assessment

This is a time series prediction problem adapted from one of our live projects.  
````
conda env create -f environment.yml
Load timeseries_skill_assessment.ipynb in jupyter notebook and follow the instructions.
````  
Don't forget to save weights from your network so we don't have to retrain it.  

If you end up using other packages, use the line below to update environment.yml and mail that back too.
````
conda env export --no-builds > environment.yml
````

2. Second skill assessment

Using your model from the first skill assessment, determine which features have the greatest impact on model performance.  Produce plots and analyses justifying your analysis (e.g., feature i is 25% more impact that feature j because ..., etc.).  

You can use existing code libraries, just explain where you got them in the code.    

Package your code, plots and analyses in a Jupyter notebook with clear documentation on how to replicate your findings.  

3. Summary

For the first skill assessment, you'll have an ipynb file and weights/model definition for your network.  

For the second skill assessment, you'll have an ipynb file.  

If you end up using other code libraries or need a new library in the anaconda environment, send the updated environment.yml too.  

Finally, in the email you send us, explain how you could make your first model better.