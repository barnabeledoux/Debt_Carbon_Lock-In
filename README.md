# Gambling-with-carbon
Codes for simulations used in the article

-All data for the different countries and computed from simulations are in the folder "data".

-The figures in pdf are available in the folder "results".

-class_carbon_gambling.py contains the class used for the various stochastic simulations to compute cumulative capital, cumulative emissions and debt. The different functions of this class are:
	-random_discrete_distribution:
		Returns a probability distribution for a specified number of horses.
	-emissions:
		Returns the cumulative emissions for the stochastic simulations.
	-step_gaussian:
		Performs a step under the assumtion that gamma is normally distributed.
	-survprob:
		Estimates the survival probability for all times up to a specified time from simulations.
	-initial:
		Initialize all variables.
	-step:
		Performs a step from the probability distribution of horses.
	-evol:
		Evolves the model for a specified number of steps.
	-plot_evol:
		Plot the evolution of a specified number of simulations.
	
-colorsarr.py contains the colors used for the various plots.

-main_countries.ipynb is a jupyter notebook used to visualize results when modeling the evolution of the capital and emissions of different countries.

-main_survival.ipynb is a jupyter notebook used to visualize results concerning the survival probability, short term growth rates, and trade-offs with the model.