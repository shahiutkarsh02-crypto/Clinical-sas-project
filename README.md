CLINICAL SAS PROJECT


About this project
This is a small practice project I worked on while learning Clinical SAS.
The goal was to understand how raw clinical data is converted into SDTM and then used to create an ADaM dataset for analysis.


What I did
Created sample raw datasets for:
  - Demographics
  - Adverse Events
  - Lab data
Converted them into SDTM format:
  - DM
  - AE
  - LB
Created an ADSL dataset by merging DM and AE
Derived some variables:
  - Age group (AGEGRP)
  - Safety flag (SAFFL)
  - TEAE (based on AE date and treatment date)
Did a simple lab shift analysis (baseline vs week 1)


QC checks
I also tried some basic checks:
  - Checked missing values
  - Removed duplicates
  - Cross-checked TEAE logic
Output
Used PROC FREQ and PROC MEANS to get simple summaries.


Why I made this
I am currently learning Clinical SAS and wanted to build a small project to practice real concepts like SDTM, ADaM, and basic analysis.


Tools used
   - Base SAS
     

Note

This is a learning project, but I tried to follow a structure similar to real clinical workflows.

