1. System requirements

MATLAB 
The provided scripts use Matlab (http://www.mathworks.com), version : '9.4.0.813654 (R2018a). No additional toolboxes are required.

2. Instructions for using the scripts with Demo

2.1. Expansion Airyscan analysis

2.1.1. Instruction
Run the 'run_airy_analysis.m' and select the 'Airy_zstack_example_5frames.mat' file in the 'demodata' folder. 
2.1.2. Expected outcome
-Images display the ch1, ch2, and merged image, segmentation map, GP image, Histogram of GP distribution within the MV and CB areas, intensity, GP, SR plot for each frame. The result images are saved as a single 'avi' file. (See the 'frames_Airy_zstack_example_10frames_GP.avi' in the 'airy_example output' folder)
-An image displays plots of intensity for ch1 and ch2, GP, and SR as a function of distance from tips of MV calculated from the entire dataset. (See the 'result_plot.fig' in the 'storm_example_output' folder) 
2.1.3. Expected run time for the demo
80 sec 

2.2. STORM image analysis

2.2.1. Instruction
Run the 'run_storm_ONI.m'. Select the 'storm_example_ch0_Lsel.csv' file for ch0, and select the 'storm_example_ch1_CD45.csv' file for ch1 in the 'demodata' folder. Modify threshold-parameters in the dialog box, for example, input '130,210' for 'X range', '180,260' for 'Y range' in the dialog box for setting a new ROI. 
2.2.2. Expected outcome
Data of the single molecules within the selected ROI for each channel, channel correction parameter, super-resoultion images for each channel, and the merged image between the two channels, Tip-locations determined by the segmentaion presented on a merged image, result of the 3D-Pair-correlaton (g(r)). 
(See the example results in the 'storm_example_output' folder)  

2.2.3. Expected run time for the demo
70 sec 

2.3. Colocalization analysis
2.3.1. Instruction
Use the function 'colocalization_analysis.m.'.Loading the example data, 'colocalization_example_ch1.mat' for ch1 and 'colocalization_example_ch2.mat' for ch2 in the 'demodata' folder. 
2.3.2. Expected outcome
Calculate the Pearson's correlation coefficient (R), Manders's overlap coefficient (MOC), Manders's correlation coefficients 1 and 2 (MCC1 and MCC2), coefficient kl and k2  [Reference: Manders, E. M. M., Verbeek, F. J. & Aten, J. A. Journal of Microscopy 169, 375-382, doi:10.1111/j.1365-2818.1993.tb03313.x (1993).]
2.3.1. Expected run time for the demo
0.2 sec 

4. Contact
Please contact yjung@lji.org for queries relating to the scripts.