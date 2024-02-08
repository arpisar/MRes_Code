# IR spectrsocopy of 2D materials

There are two different sets of codes in MRes_Code repository:
- WORKFLOW and
- MODEL

## 1 WORKFLOW_
WORKFLOWs are for processing the data straight after FTIR measurements. They allow you to:
1. Get the correct units: transmission in percent and wavelenth in um (WORKFLOW_process)
2. Plot the measurements (WORKFLOW_plot)
3. Do nearest neighbour averaging for noise reduction (WORKFLOW_Nearest_Neighbour_Averaging)

WORKFLOWs are only meant to be run once per set of measurements since they produce new files each time they run.

## 2 MODEL_


### 2.1 MODEL_thickness
A simulation of the transmission of an insulator (Sapphire), and how it changes depending on thickness.
Literature data from two different sources (Palik et al. and Lumerical) are used to test the theory and both are then compared to FTIR measurements.

### 2.2 MODEL_temperature
Plots the cold temperature sapphire measruements. 
Colour coding - Blue : Cold, Red: Warm. Coldest = 77K, Warmest = 290K.






