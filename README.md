# DumpAnalysis-HLASM

Reference: MVS 3.8 Dump Analysis - Part II - M16 (youtube video: https://youtu.be/uGsozrcPTbY)
Github:  https://github.com/moshix/abendanalysis

SUMMARY
=======
This is a study of a S0C7 abend (abnormal end) using the IBM High Level Assembler for z/OS
HLASM R6.0 (PTF UI65623). As a followup to Moshix videos on MVS3.8 Dump Analysis, we would like to 
observe the differences between dump analysis in a MVS3.8 and z15 environments.

ENVIRONMENT
=============
OS:         z/OS 02.03.00 *** Assembler:  HLASM 5696-234, release 6.0
 *** CPU:        8561-T01

DETAILS
=======
Ran the Moshix JCL (with very little modifications) on the IBM training LPAR, which makes available 
a processor type 8561-T01.

The job name was S0C7DMP.

Files as as follows:
1. JCL: AbendAnalysis_S0C7_JCL.txt
2. Compile Listing:  AbendAnalysis_S0C7_CList.txt
3. Abend dump: AbendAnalysis_S0C7_S0C7Dump.txt 
