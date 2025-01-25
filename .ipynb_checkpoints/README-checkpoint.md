# Bayesian Statistics

Here is our project for the course of Bayesian Statistics of third year at ENSAE, the group is composed of Guillaume Lévy, Aymeric Perrin and Pierre Perrigault.

In this GitHub, you have the main (and only) file to open : Code final.ipynb containing our work. 

## How it is organised ?

In the first cells, we define the useful functions for our project, that is to say the log-likelihood of our posterior, the program to run the maximization, and additionnal functions. 

After that, you will find a cell where we charge the data and run the functions above. In the beginning of this cell, you can choose the data you want to use (i.e "mat" for the data used in the paper and "log" or "logger" for the data we introduced). For this, you only have to change the value of the variable "data". Then, by running the cell you will begin the optimization and you will obtain the MSFE graphs for the variables and transformations chosen, with PLR and a simple Minnesota prior. 

The cells after are those we used for the additionnal graphs in our report, to compare the results with different initial parameters for the hyperprior of phi. As before, you can choose which dataset you want to use, for Germany or for the US, and after there are the plots for the different hyperpriors. 

Thanks, and do not hesitate if something is not clear about our code or something else, t