# ArcGIS
A sample of my ArcGIS mapping projects completed during a GIS course at Oberlin College, fall 2017.
Labs 1, 2, and 6 did not involve creating maps, so their output is not included in this repository. 

I have also included a final project completed by myself and Kopo Oromeng called [The State of the Lake](https://github.com/valhella/ArcGIS/blob/102fdbfe4c17f4941ba6154d772be4f7c5ca1b6a/The%20State%20of%20the%20Lake%20poster.md), which investigates algal blooms in Lake Erie.

## Summary of Competencies
### Lab 1: Introduction to ArcGIS
-	Goals: Create folders, navigate windows explorer and Arc Catalog, Arc Map, add data, load extensions, practice Arc Scene
-	Tools: Hillshade
### Lab 2: Projections
-	Goals: Exploring geographic + projected coordinate systems
-	Tools: Define projection, project, project raster, locating metadata
### Lab 3: Sinuosity [(View outputs)](https://github.com/valhella/ArcGIS/blob/9508cf6ecff3b822373e1eff6fd8b987d39f3fc2/Lab%203:%20Sinuosity.md)
-	Goals: See how a river changed over time, get familiar with python, understand how to digitize things
-	Tools: Create shapefile (we used polyline in this one) and project it, Add fields to attribute tables, digitize river paths using editor toolbar, modify python script to allow for correct calculation of sinuosity, sinuosity tool
### Lab 4: Hurricanes [(View outputs)](https://github.com/valhella/ArcGIS/blob/102fdbfe4c17f4941ba6154d772be4f7c5ca1b6a/Lab%204:%20Hurricanes.md)
-	Goals: Show path of one hurricane, its projected paths from different time frames, the error associated with the path, and the areas affected by different strength winds. Also showed which counties are hit by hurricanes the most, and which counties had the most old people that would be affected by hurricanes. 
-	Tools: Display XY data, buffer, point to line, merge, select by attributes, dissolve, spatial join
### Lab 5: Tsunamis and Sea Level Rise [(View outputs)](https://github.com/valhella/ArcGIS/blob/102fdbfe4c17f4941ba6154d772be4f7c5ca1b6a/Lab%205:%20Tsunamis%20and%20Sea%20Level%20Rise.md)
-	Goals: estimate how many people would be affected by sea level rise or a tsunami, create data driven map book
-	Tools: 
  - ASCII to raster tool, define projection, project raster, float to raster, hillshade, raster domain, clip
  - Reclassify, raster to polygon, select by attributes and create layer from selectionexport, select by location, python select by location
  - Zonal statistics as table, intersect, grid index (cartography)
### Lab 6: Evaluating the effect of scale on raster calculations 
-	Goals: Test hypothesis made in Montgomery and Brandon (2002) that mean local relief and slope give the same information but that mean local relief is less dependent on the scale of the raster; learn how to make and run a python function from scratch; understand how grid size effects calculation speed and mean local relief and slope calculations. 
-	Tools:
    - Clip, project raster
    - Slope, raster calculator to make slope-calculated dem file data rounded to nearest integers, export data to excel to make scatter plots
    - Python: created function, ran function, saved file (focal statistics)
    - Created histograms in Excel to compare slope and mean local relief
### Lab 7: Rainfall patterns and drainage density on the big island of Hawaii [(View outputs)](https://github.com/valhella/ArcGIS/blob/102fdbfe4c17f4941ba6154d772be4f7c5ca1b6a/Lab%207:%20Rainfall%20patterns%20and%20drainage%20density%20on%20the%20big%20island%20of%20Hawaii.md)
- Goals: Learn how to create a streams polyline starting with a DEM using flow accumulation tool, extract stream networks and watersheds from DEMs to see if there is a correlation between precipitation and the way a stream network develops on a mountain, and calculate drainage density. 
- Tools: 
  - Define projection, project, project raster
  - Slope, hillshade, fill, flow direction, flow accumulation, reclassify, raster to polyline
  - Create shapefile, add points for outflows of streams on streams file we made
  - Use python script to create watersheds, turn the watersheds into polygons, calculate zonal statistics with each polygon as a zone, and then join the resulting statistical information with the shapefile.
  - Merge watersheds, calculate geometry to find watershed area and length of streams, combine lines(?), excel plotting
### Lab 8: Large Woody Debris available to Plum Creek in the Oberlin Arb [(View outputs)](https://github.com/valhella/ArcGIS/blob/102fdbfe4c17f4941ba6154d772be4f7c5ca1b6a/Lab%208:%20Large%20Woody%20Debris%20available%20to%20Plum%20Creek.md)
-	Goals: Convert LiDAR data to a variety of rasters, calculate tree heights, and figure out how much large woody debris is available to plum creek in the arb. 
-	Tools:
    -	Point file information, create LAS dataset
    - Save gps waypoints as shapefile, merge, project, mosaic to new raster, new shapefile polyline, define projection, LAS dataset to raster
    - Python: Make LAS Dataset Layer, LAS dataset to raster, Raster, Map Algebra, Euclidean distance
### Lab 9: Remote Sensing and Python [(View outputs)](https://github.com/valhella/ArcGIS/blob/102fdbfe4c17f4941ba6154d772be4f7c5ca1b6a/Lab%209:%20Remote%20Sensing%20and%20Python.md)
- Goals: Develop a land cover raster dataset and compare it to official USGS land use dataset. Determine whether Landsat 7, Landsat 8, or EO-1 produces the best multispectral imagery best suited for land cover classification. Learn how to make true-color and false-color imagery. Write code to simplify process in future.
- Tools:
  - Create new shapefile, define projection, project
  - Python: ListRasters, ExtractByMask
  - Composite bands, iso cluster unsupervised classification tool
