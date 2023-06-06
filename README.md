# DAR1_config

This repository holds the configuration files for the MIT DARWIN model to be used with the julia tool [DAR1](https://github.com/barbara42/Dar_One). 
See the DAR1 respository for more information about set-up and tutorials. 

The config files are broken up into three folders 
1. `/code` - contains the *build-time* code specifying how MIT DARWIN will be structured, notably number of grid cells, number of tracers, number of plankton groups, and whether any tracers will be held constant or not. 
2. `/input` - contains *run-time* options for MIT DARWIN, such as temperature, nutrient levels, tracer abundance, light, sampling frequency, length of run, etc. 
3. `/run` -  empty folder where all your runs will be saved in sub-folders
