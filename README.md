# project-cycling
Visualization and analysis of my cycling adventure.
## Data import and cleaning:
this part of the project processes data for analysis and visualization
1. Read and Combine Fit Files:
   * Read *.fit files from the designated folder.
   * Combine the values from these files into a single raw CSV file.
2. Save Feature Units to Excel:
   * Save the feature units of the raw data to an Excel file for reference during conversion.
3. Convert Raw File Units:
   * Convert the units of the raw file to more readable units.
   * Save the converted data to another file.
4. Handle Missing Values:
    * Identify missing values in the fit files.
    * Calculate the percentage of missing values for each file.
    * Evaluate the usability of each file based on missing data percentages.
    * Label the main activities file and unit converted CSV file for fit files accordingly.
#
## Heatmap:
This Python script generates a heatmap using the Folium library to visualize cycling adventures based on GPS coordinates. The script reads data from a CSV file containing ride information, fills missing values in latitude and longitude, and then creates a heatmap centered at the mean coordinates of the data.
