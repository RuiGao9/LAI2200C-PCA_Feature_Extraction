# LAI2200-PCA
## Contact
Rui Gao<br>
Rui.Gao@usu.edu | Rui.Gao@aggiemail.usu.edu

## Brief introduction:
- Main purpose for this script is extracting the measurement record number (ID), the ground LAI measurements (LAI), the corresponding measurement time including date and time (Time), the latitude of the ground measurement (Lat), and the longitude of the ground measurement (Lon). 
- This code written based on my experience when review the fomat and the patter of the table (txt file) gained from the LAI-2200 analyzer. The key is that the ID remains unchanged in the text file viewed by FV2200 (software). Current test are all correct, potential issues are welcome to eamil Rui.

## Required inputs:
A ".xlsx" format file is required for this code, and this is the only manual work that we need to do. A demo ".xlsx" file, "LAI_Well_0720B.xlsx" is attached in this repository. The original ".txt" file, "WEL0720B.TXT", is also attached in this repository. By using the software called "FV2200", I copy and past the data into the ".xlsx" file. 4 sheet-name are required as the same like I showed in the ".xlsx" sheet, otherwise, the corresponding part of this code is needed to modify. For the ".xlsx" file, the first 3 sheets come from the ".txt" file. Direct copy and past is sufficient. The 4th sheet called "Current_new" is the main part of the 2nd sheet called "Current". Being careful about the format should be enough to run this code successfully.

## Gentle reminder
One repository called [LAI-2200C](https://github.com/Mahyarona/LAI-2200C) which is built by Dr. [Aboutalebi](https://scholar.google.com/citations?user=6mqPhOMAAAAJ&hl=en) is much easy to use. It is a Matlab based script. I haven't noticed this repository after I finished my repository. Users can adopt either one accordingly.
