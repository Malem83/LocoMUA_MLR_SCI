# LocoMUA_MLR_SCI
Import EMG data from Spike2 for analysis in MATLAB.

These scripts were written for MATLAB by Maxime Lemieux, research assistant in the laboratory of Prof. Frédéric Bretzner at Université Laval, Québec, Canada. They process data sampled and processed by Spike2 (CED). Data were acquired with a Power3 unit. Scripts were used for a peer-reviewed study. The design requires 4 muscles (filtered traces and raster of spikes) and a timebase for stim. Scripts were intended for longitudinal spinal cord injury studies (4 timepoints: before, week 1, week 4 and week 7).

First run LocoAnalysis.m to import data and pre-process the database

Then, run LocoAnalysis2.m to process the data. It calls the script 2a, 2b and 2c. Script 2a evaluates the locomotor phase (0 to 1, triggered on flexor burst) when occurs the stimulation. Script 2b computes the response in terms of motor unit density and amplitude. Finally, 2c sorts data according to the phase or the occurrence of stops occurring before or after stimulationé
