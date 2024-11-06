# Calculate Labor Productivity Change Due to Heat Stress
**By: Iman haqiqi, Department of Agricultural Economics, Purdue University**

First version: October 4, 2024

Contact: ihaqiqi@purdue.edu

**How to cite:**

This code is a slightly modified version of the codes used for: Saeed, W., I. Haqiqi, Q. Kong, M. Huber, J. R. Buzan, S. Chonabayashi, K. Motohashi, and T. W. Hertel. "The poverty impacts of labor heat stress in West Africa under a warming climate." Earth's Future 10, no. 11 (2022).  https://doi.org/10.1029/2022EF002777

###  Objective
This code takes the WBGT estimates based on climate projections and converts it to labor productivity change for use in economic models.

### File structure
The inputs are WBGT estimates with the following details:

- warming scenario 1C, 2C, 3C, 4C, 5C
- climate models: 
  * "ACCESS_CM2",
  * "CMCC-CM2-SR5",  
  * "EC-Earth3_r1i1p1f1",     
  * "EC-Earth3_r3i1p1f1",    
  * "EC-Earth3_r4i1p1f1",     
  * "HadGEM3-GC31-LL",       
  * "HadGEM3-GC31-MM", 
  * "BCC-CSM2-MR", 
  * "MPI-ESM1-2-HR_r1i1p1f1", 
  * "MPI-ESM1-2-HR_r2i1p1f1",  
  * "MPI-ESM1-2-LR", 
  * "MRI-ESM2-0", 
  * "MIROC6", 
  * "KIOST-ESM" 
- indoor vs outdoor
- daytime vs allday
- work intensity: w200, w300, w400, w600

The outputs are labor productivity change for farmworkers in the agricultural sector by
- climate model and
- warming scenario
