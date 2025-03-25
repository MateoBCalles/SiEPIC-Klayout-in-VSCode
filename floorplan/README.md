Pulled from SiEPICfab_ZEP04_Shuksan_20250215 README.md

# Submission Process Slightly modified
We are using an automated merging script to combine the layouts.

Step 1: In this step, you allocate yourself space in the shared design space. 

Step 2: In this step, you create your personal design layout function using Apodized Bragg Reflector.ipynb as an example. Commit your changes as your design changes.

Step 3: In this step, you merge your design layout file to the merged layout file to be submitted.



## Detailed instructions:

1. Step 1:  
![01_floorplan](tutorial/01_floorplan.gif)
  - Pull from GitHub the repo 
  - Open 'gds_floorplan'.
  - Open the floorplan layout file inside the folder.
  - Create a box using the 'FloorPlan' layer in which your design will fit in.
  - Turn the box into a cell with your name (Ctrl+Shift+M), Edit → Selection → Make Cell
  - Save the layout
  - **IMPORTANT** Commit back to GitHub. 

2. Step 2:  
  - Open the notebook example: "Apodized Bragg Reflector.ipynb"
  - This copys the floorplan from the mainchip floorplan .oas file in gds_floorplan
  - Adjust accordingly
  - Comments in the example should walk you through whats necessary
  - **IMPORTANT** Commit back to GitHub. 

3. Step 3:
![03_merge](tutorial/03_merge.gif)
  - Open the macro editor in KLayout (F5)
  - Right click anywhere on the left panel and click 'add location'
  - Navigate to the 'merge_script' directory in this repository and click 'OK'
  - open the 'merge_script' file from the macro editor and run it.
  - Check if your design has been merged in the 'gds_merge' layout file 
  - **IMPORTANT** Commit back to GitHub. 
