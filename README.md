# COVID-19 Research

A Jupyter Notebook simulation using the SEIR model for the course of a pandemic. The numbers used were (extremely rough) approximations of the University of Virginia's population.
The SEIR model is a compartmental model which used nonlinear differential equations to model individuals which are susceptible, exposed, infected, and recovered. The exposed compartment exists due to an incubation stage of infection that lasts approximately 6 days, specific to COVID-19. The model assumes people carry lifelong immunity to a disease upon recovery, which hasn't been disproven rigorously for COVID-19.

<p align="center">
  <img src="seir_graph.jpg" width="500">
</p>

Packages:
Pandas and numpy to process data, scipy odeint to solve the differential equations numerically, and matplotlib to plot the values.

https://www.cdc.gov/coronavirus/2019-ncov/hcp/planning-scenarios.html
