# ArcGIS
A sample of my ArcGIS mapping projects completed during a GIS course at Oberlin College, 2017.

## Summary of Competencies
Lab 1: Introduction to ArcGIS
•	Goals: Create folders, navigate windows explorer and Arc Catalog, Arc Map, add data, load extensions, practice Arc Scene
•	Tools: Hillshade
Lab 2: Projections
•	Goals: Exploring geographic + projected coordinate systems
•	Tools: Define projection, project, project raster, locating metadata
![image](https://user-images.githubusercontent.com/45399983/133864085-5fcb3def-7fcc-4c31-89a5-c5f329a900e4.png)
Lab 3: Sinuosity
  •	Goals: See how a river changed over time, get familiar with python, understand how to digitize things
  •	Tools: Create shapefile (we used polyline in this one) and project it, Add fields to attribute tables, digitize river paths using editor toolbar, modify python script to allow for correct calculation of sinuosity, sinuosity tool
Lab 4: Hurricanes
  •	Goals: Show path of one hurricane, its projected paths from different time frames, the error associated with the path, and the areas affected by different strength winds. Also showed which counties are hit by hurricanes the most, and which counties had the most old people that would be affected by hurricanes. 
  •	Tools: Display XY data, buffer, point to line, merge, select by attributes, dissolve, spatial join
Lab 5: Tsunamis and Sea Level Rise
  •	Goals: estimate how many people would be affected by sea level rise or a tsunami, create data driven map book
  •	Tools: 
    o	ASCII to raster tool, define projection, project raster, float to raster, hillshade, raster domain, clip
    o	Reclassify, raster to polygon, select by attributes and create layer from selectionexport, select by location, python select by location
    o	Zonal statistics as table, intersect, grid index (cartography)
Lab 6: Evaluating the effect of scale on raster calculations 
  •	Goals: Test hypothesis made in Montgomery and Brandon (2002) that mean local relief and slope give the same information but that mean local relief is less dependent on the scale of the raster; learn how to make and run a python function from scratch; understand how grid size effects calculation speed and mean local relief and slope calculations. 
  •	Tools:
    o	Clip, project raster
    o	Slope, raster calculator to make slope-calculated dem file data rounded to nearest integers, export data to excel to make scatter plots
    o	Python: created function, ran function, saved file (focal statistics)
    o	Created histograms in Excel to compare slope and mean local relief
Lab 7: Rainfall patterns and drainage density on the big island of Hawaii
  •	Goals: Learn how to create a streams polyline starting with a DEM using flow accumulation tool, extract stream networks and watersheds from DEMs to see if there is a correlation between precipitation and the way a stream network develops on a mountain, and calculate drainage density. 
  •	Tools: 
    o	Define projection, project, project raster
    o	Slope, hillshade, fill, flow direction, flow accumulation, reclassify, raster to polyline
    o	Create shapefile, add points for outflows of streams on streams file we made
    o	Use python script to create watersheds, turn the watersheds into polygons, calculate zonal statistics with each polygon as a zone, and then join the resulting statistical information with the shapefile. 
    o	Merge watersheds, calculate geometry to find watershed area and length of streams, combine lines(?), excel plotting
Lab 8: Large Woody Debris available to Plum Creek in the Oberlin Arb
  •	Goals: Convert LiDAR data to a variety of rasters, calculate tree heights, and figure out how much large woody debris is available to plum creek in the arb. 
  •	Tools:
    o	Point file information, create LAS dataset
    o	Save gps waypoints as shapefile, merge, project, mosaic to new raster, new shapefile polyline, define projection, LAS dataset to raster
    o	Python: Make LAS Dataset Layer, LAS dataset to raster, Raster, Map Algebra, Euclidean distance
Lab 9: Remote Sensing and Python
  •	Goals: Develop a land cover raster dataset and compare it to official USGS land use dataset. Determine whether Landsat 7, Landsat 8, or EO-1 produces the best multispectral imagery best suited for land cover classification. Learn how to make true-color and false-color imagery. Write code to simplify process in future.
  •	Tools:
    o	Create new shapefile, define projection, project
    o	Python: ListRasters, ExtractByMask
    o	Composite bands, iso cluster unsupervised classification tool
![image](https://user-images.githubusercontent.com/45399983/133863865-010ce126-4e1f-45d6-8014-4c373ad37f15.png)
