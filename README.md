maxent-batch
============

Enable MaxEnt Ensembles

By default [MaxEnt](http://www.cs.princeton.edu/~schapire/maxent/) takes point location observations of species presence/absence and gridded data reflecting status of environmental variables (eg [Bioclim](http://www.worldclim.org/bioclim) variables). When running against climate model outputs the typical use-case is to run one MaxEnt configuration against an ensemble of climate model derived environmental variables, creating an ensemble of MaxEnt models. The bash scripts provided here enable that use-case.


