# Proctor Creek Water Quality Analysis 
## with the West Atlanta Water Alliance
Taylor Howell, Quinn Knapper, John Pederson, Brantley Proffitt, and Sean Warren
Profs. Andrew Medford and Eva Dyer
COE 3803: Data Analytics for Engineers

![Multi-mass and Spring 2D](https://github.com/seankwarren/Modeling-and-Simulation-Samples/blob/main/01-NewtonianPhysics/SpringsAndPendulums/multi-mass-and-spring-2d.gif?raw=true)
![poster](https://github.com/seankwarren/Water-Quality-Analysis/blob/master/Poster.jpg?raw=true)

-----

Contents:

	data/
		Rivers_Streams_Atlanta_Region.shp	#Atlanta Regional Commission data containing geospatial waterway information
		Rivers_Streams_Atlanta_Region.cpg
		Rivers_Streams_Atlanta_Region.dbf
		Rivers_Streams_Atlanta_Region.prg
		Rivers_Streams_Atlanta_Region.shx
	DataSelectionTotalColiform.ipynb		#Jupyter Python notebook that exports total coliform water data
	DataSelectionEColi.ipynb				#Jupyter Python notebook that exports e coli water data
	1D_analysis.ipynb						#Jupyter Python notebook that conducts preliminary one dimensional analysis
	AnalysisModel.ipynb						#Jupyter Python notebook that conducts detailed feature analysis
	
-

To re-run the Proctor Creek Water Quality Analysis, run each Jupyter Python Notebook individually in the following order:
	1) DataSelectionTotalColiform.ipynb
	2) DataSelectionEColi.ipynb
	3) 1D_analysis.ipynb
	4) AnalysisModel.ipynb

*Note: Some libraries used in the analysis may not be currently installed. The geopandas, plotly, and pingouin libraries are not common in base python library collections. If errors are encountered begin troubleshooting by running a !pip install command for libraries causing errors
