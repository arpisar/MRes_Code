# IR spectroscopy of 2D materials

### About the project:
The aim of my project is to probe the optical properties a 2D material -Platinum diselenide (PtSe2)- in extreme cold temperatures with the use of liquid nitrogen.
I use programming to make sense of my measurements and to compare them to literature and theory.

The PtSe2 sample I work with is deposited on a sapphire substrate, which is why the initial part of my research consists of probing optical properties of *sapphire* in extreme cold conditions.

Below, I've tried to make sense of my *workflow and the way I compile and analyse measurements*.

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

MODELs are for 'making sense' of the data (compiling, analysing, comparing to theroy) after processing.

### 2.1 MODEL_thickness
A simulation of the transmission of an insulator (Sapphire), and how it changes depending on thickness.
Literature data from two different sources (Palik et al. and Lumerical) are used to test the theory and both are then compared to FTIR measurements.

### 2.2 MODEL_temperature
Plots the cold temperature sapphire measruements. 
Colour coding - Blue : Cold, Red: Warm. Coldest = 77K, Warmest = 290K.






