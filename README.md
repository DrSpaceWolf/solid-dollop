# solid-dollop
Script that analyzes force, displacement data and generates pass/fail based on predetermined criteria. Prompts user to select directory. Defines pass/fail thresholds for force and work. Pulls data and populates into data structure. Evaluates force vs. displacement. Evaluates work. Plots the f-d and w-d graphs
 1) User prompted to select directory containing 'data' folder, which contains the .dat files. Do not select the 'data' file itself when prompted.
 2) .dat files to contain 4 rows of headers (ignored in code) If headers are different, code must be adjusted.
 3) .dat files to contain 7 columns of data: Load, Disp, Stress, Time, Temp, Axial, Transverse, Chans 1-20
 4) Force values in lbf; displacement in in.; work in in*lbf
 5) Defined for up to 800 separate .dat files and up to 800 data points per .dat file. If file size exceeds this value, adjust maxRows and maxHeaderLength accordingly. 
