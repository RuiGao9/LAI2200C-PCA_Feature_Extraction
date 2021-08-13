# LAI2200-PCA
## Contact
Rui Gao<br>
Rui.Gao@usu.edu | Rui.Gao@aggiemail.usu.edu

## Brief introduction:
- Main purpose for this script is extracting the measurement record number (ID), the ground LAI measurements (LAI), the corresponding measurement time including date and time (Time), the latitude of the ground measurement (Lat), and the longitude of the ground measurement (Lon) from the "txt" file saved in [LAI2200C Plant Canopy Analyzer](https://www.licor.com/env/products/leaf_area/LAI-2200C/). 
- This code written based on my experience when review the fomat and the patter of the table (txt file) gained from the LAI-2200 analyzer. The key is that the ID remains unchanged in the text file viewed by FV2200 (software). Current test are all correct, potential issues are welcome to eamil Rui.

## Required inputs:
A ".xlsx" format file is required as input for this code, and this is the only manual work that we need to do (preparing this EXCEL sheet). <br>
A demo ".xlsx" file, "LAI_Well_0720B.xlsx" is attached in this repository. The original ".txt" file, "WEL0720B.TXT", is also attached in this repository. <br>
By using the software called "FV2200", I copy and past the data from the software into the ".xlsx" file. 4 sheet-name are required as the same like I showed in the ".xlsx" sheet, otherwise, the corresponding part of this code is needed to modify. <br>
For the ".xlsx" file, the first 3 sheets come from the ".txt" file viewed by "FV2200" software. Direct copy and past is sufficient. The 4th sheet of the ".xlsx" file called "Current_new" is the main part of the 2nd sheet called "Current". <br>
Being careful about the format should be enough to run this code successfully.<br>

## Main Scientific References
Rui Gao, Alfonso Torres-Rua, Ayman Nassar, Joseph Alfieri, Mahyar Aboutalebi, Lawrence Hipps, Nicolas Bambach Ortiz, Andrew J. McElrone, Calvin Coopmans, William Kustas, William White, Lynn McKee, Maria del Mar Alsina, Nick Dokoozlian, Luis Sanchez, John H. Prueger, Hector Nieto, Nurit Agam, "Evapotranspiration partitioning assessment using a machine-learning-based leaf area index and the two-source energy balance model with sUAV information," Proc. SPIE 11747, Autonomous Air and Ground Sensing Systems for Agricultural Optimization and Phenotyping VI, 117470N (12 April 2021); https://doi.org/10.1117/12.2586259

## Gentle reminder
One repository called [LAI-2200C](https://github.com/Mahyarona/LAI-2200C) which is built by Dr. [Aboutalebi](https://scholar.google.com/citations?user=6mqPhOMAAAAJ&hl=en) is much easy to use. It is a Matlab based script. I haven't noticed this repository after I finished my repository. Users can adopt either one accordingly.
