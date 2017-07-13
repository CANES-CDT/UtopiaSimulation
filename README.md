# Utopia Simulation

Project for the development of a Netlogo simulation to illustrate concepts from
non-equilibrium systems modelling in an accessible way. This formed part of the
[CANES](https://www.kcl.ac.uk/innovation/groups/noneqsys/index.aspx) CDT's
contribution to the [Paths to Utopia
exhibition](https://www.kcl.ac.uk/Cultural/Cultural-Institute/Utopia2016/Utopia2016.aspx),
which was organised by the King's Cultural Institute in the Somerset House East
Wing in September and October 2016. This was part of the wider [Utopia 2016
](http://utopia2016.com/) event which took place throughout the year in
Somerset House.

## Simulation overview

The simulation uses the [NetLogo](https://ccl.northwestern.edu/netlogo/) Agent
Based Modelling environment to provide a graphical interface to explore
non-equilibrium dynamics which can be explored as a virus spreads through a
network of individual people. We made use of Uri Wilensky's excellent 'Virus on
a Network' model which comes with NetLogo's model library as the basis for the
simulation. To explore non-equilibrium dynamics, We simply added functions to
deliberately infect a random subset of the modelled population, and to track
whether the system was at equilibrium or not. Uri Wilensky's original model is
made available under the Creative Commons Attribution-NonCommercial-ShareAlike
3.0 License. To view a copy of this license, visit
https://creativecommons.org/licenses/by-nc-sa/3.

## Running the simulation

To run the simulation:

1. Download Netlogo (for free) from their
[website](https://ccl.northwestern.edu/netlogo/)
2. Clone this repo or download Vir-Network-Mod.nlogo
3. Open Vir-Network-Mod.nlogo in Netlogo
4. Play with the sliders to experiment with the effects of different model
parameters
5. Press the 'go' button

You can also press the 'Infect People!!' button to infect people (a default of
10% of the total population) while the simulation is running to see the effects
of this on the dynamics.