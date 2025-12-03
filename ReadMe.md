# Title: Code Sharing Assignment

## Subtitle: Story Tracts Male percentage


## General information
**Author Name**: Srikanth Panthulugiri <br>
**Date**: 2025-12-02 <br>
**Purpose of the Code**:<br> Convert GeoJSON to FC, Join CSV attribute,
Apply symbology, and create matplotlib graph.

**Data Accesssed**: Census Tract 


**Follow these steps to run the Story County Census analysis using the provided Python toolbox and datasets.
This guide is tailored to the folder structure of your project:**

## FILE DIRECTORY

```
code_sharing_assignment
├── ArcGIS_Workup
│       ├── ArcGIS_map
│       ├── GIS output
│       └── male_percentage_plot.png
├── Dataset
│    ├── Census Tract-2025-12-02T15_41_39.086Z 
│    │      └──P504577759-2025-11-2009564883.json
│    └── story_tracts_malepercentage_cleaned.csv
├── StoryCountyToolbox-Files
└── ReadMe.md

```

---

1. Open the Project Folder in ArcGIS Pro<br>
Launch ArcGIS Pro.<br>
Open the Catalog pane.<br>
Right-click Folders → Add Folder Connection.<br>
Add the main project folder:<br>

##code_sharing_assignment##

This allows ArcGIS Pro to access your toolbox and data files.

2. Load the Python Toolbox<br>
Inside the Catalog pane, navigate to:
<br>code_sharing_assignment/StoryCountyToolbox-Files
<br>Right-click:
<br>StoryCountyCensusToolbox.pyt
<br>Select Add to Project.
<br>The tool Census Data Processing Tool will now be available under Toolboxes in your project.

3. Prepare Input Data<br>You will supply two files stored in the Dataset folder:
<br>Census CSV File (Demographic Data)
<br>code_sharing_assignment/Dataset/story_tracts_malepercentage_cleaned.csv

GeoJSON File (Census Tract Boundaries)
code_sharing_assignment/Dataset/Census Tract-2025-12-02T15_41_39.086Z/P504577759-2025-11-2009564883.json
<br>These contain male population percentage and census tract geometry for Story County.

4. Choose the Output Workspace
<br>Select a folder where all outputs will be stored, such as:
<br>code_sharing_assignment/ArcGIS_Workup/GIS output
<br>This folder will hold:
<br>The converted shapefile
<br>Joined DBF table

Intermediate outputs
<br>The final PNG graph
<br>Make sure this folder already exists before running the tool.

5. Provide the PNG Output Location
<br>When prompted for Save Graph PNG Output Location, give the full path including the filename:
<br>code_sharing_assignment/ArcGIS_Workup/GIS output/male_percentage_plot.png
<br>The file does not need to exist — the tool generates it automatically.

 
---