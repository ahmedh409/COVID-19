# COVID-19 Research

A Jupyter Notebook simulation using the SEIR model for the course of a pandemic. The numbers used were (extremely rough) approximations of the University of Virginia's population.
The SEIR is a compartmental model which adds an “Exposed” state (compared to SIR) for individuals that have contracted the disease but are not yet infectious. This uses the fact that there is an incubation stage of infection that lasts approximately 6 days. The model assumes people carry lifelong immunity to a disease upon recovery, which hasn't been disproven for COVID-19.

<p align="center">
  <img src="seir_graph.jpg" width="500" align="center">
</p>

Packages:
Pandas and numpy to process data, scipy odeint to solve the nonlinear differential equations numerically, and matplotlib to plot the values.

https://www.cdc.gov/coronavirus/2019-ncov/hcp/planning-scenarios.html
