# Project Name : Bike Sharing Assignment
> The purpose is to find the best relationship between the demand('cnt' variable) and the other predictor variables given in input dataset.


## General Information
* As there are multiple predictor variables, I have used Multiple Linear Regression technique of AI\ML to find the above mentioned relationship
* Used following python libraries for the analysis:
	- numpy, pandas for reading and processing the data
	- seaborn and matplotlib for plots, charts
	- sklearn(RFE) for coarse variable selection and statsmodel for finer variable selection using Multiple Linear Regression techinque.

* Concluded the following relatioship:  cnt(demand) = -0.0132 + 0.9862*registered + 0.1054*sat + 0.0241*clearWithFewClouds (see the bpatil_BikeSharingAssignment.ipynb for details on the variables and analysis)

=========================================
Variable characteristics
=========================================	
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered.
	- sat: Saturday, or 'weekday' variable with value 6 as in input dataset.
	- clearWithFewClouds: This is weathersit variable with value 1 as defined below in input dataset. 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy

* [Acknowledgements](#acknowledgements)
I have used data.csv from following publications as input (train and test) data:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}


## Contact
Created by [@BhagavantraoPatil] - feel free to contact me!