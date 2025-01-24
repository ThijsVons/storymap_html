This GitHub page is to host HTML files for showing data for the Data Science for Smart Environments project from the Traffic 1 group on and ArcGIS Storymap.

# Code and data Traffic content:
This folder contains code for processing raw data. This processed data was passed onto groupmates.
Also the code for the free flowing highway analysis is in this folder.
There is also a word document containing the method of gathering data from NDW Dexter.
To show the results on an ArcGIS Storymap HTML files were created to link to in the story map.
In these HTML files the user can select a result plot to be shown: https://github.com/ThijsVons/storymap_html/tree/main.

# Packages to Install:
- os
- matplotlib.pyplot
- numpy
- pandas
- shutil
- scipy
- time

# File Structure:
Code and data Traffic
  * README.md
  * Traffic_project_code
    * traffic_data_processing.py
    * freeflow_traffic_data.py
    * traffic_project_functions.py
    * A2_Breukelen_seperate_lanes_data_processing.py
  * Data
    * A2_Breukelen
    * A27_Breda_Breda_year
    * A58_Kruingingen_Oranjeplaat_year
    * A58_Tilburg_Breda
    * A58_Tilburg_Breda_year
  * Results
    * A58_Zeeland
      * day
      * day_cutout
      * night
      * night_cutout
      * merged
      * merged_cutout  
  * Dexter NDW Data Gathering Methods.docx
