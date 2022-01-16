# Lesson 7: Environment Variables
Latest Submission Grade 100%
<br/>

**Question 1 What are Environment Variables in ArcGIS?** 
1 / 1 point

Environment
Variables are variables specific to
Geoprocessing tools in ArcGIS that represent environmental data such as
rainfall, air pollution, or population of a species. 

Environment Variables are specific to the Environmental
Analysis toolset and represent environmental data used by all tools in that
family.

**Environment Variables are a group of common settings shared among Geoprocessing tools that change tool processing behavior.**

Environment Variables are the settings specific to a single Geoprocessing tool that
change how it operates.
Correct


<br/>
<br/>

**Question 2 Why is the Output
Coordinate System Environment Variable important? Check all that apply.**
2 / 2 points

**The Output
Coordinate System Environment Variable sets what projection is used for
geoprocessing tools.**
Correct

**The Output Coordinate System Environment Variable is important because running Geoprocessing tools that re-project data can cause small errors. This reprojection occurs automatically when tool inputs are in different coordinate systems, so the Output Coordinate System variable directs that behavior.**
Correct

The Output
Coordinate System Environment Variable is only used in raster specific
tools.

The Output
Coordinate System Environment Variable determines what projection system is
used when exporting a final map product.



<br/>
<br/>

**Question 3 What is the purpose of the Extent Environment Variable?**
1 / 1 point

The Extent Environment Variable is the only way to limit Geoprocessing to a specific area.

The Extent
Environment Variable affects the output of ArcGIS when printing or
exporting, but does not limit the view when working on the data.

**The Extent
Environment Variable allows the user to set a specific area on which to
perform Geoprocessing and is useful if you plan to run multiple Geoprocessing
actions.**

The Extent Environment Variable limits the
view extent of the ArcGIS environment. It is useful with large datasets and
slower machines to keep the rendering time low.
Correct

While not the only way to restrict the extent of
a Geoprocessing tool, the Extent Environment
Variable is useful because it allows the user to make a selection once, then
have it available for future use.



<br/>
<br/>

**Question 4 What does the Snap Raster Environment Variable do?**
1 / 1 point

**The Snap Raster Environment Variable sets a
base raster and forces other raster(s) in the analysis to begin from a common
origin point.**

The Snap Raster Environment Variable takes an input feature class and positions
all rasters in the analysis relative to that feature class. 

The Snap
Raster Environment Variable causes data to be displayed in a different
projection system and makes it appear to snap into position.

The Snap Raster Environment Variable sets the projection used in a Geoprocessing tool to the projection used by its input. It is analogous to the vector data specific Environment Variable Output Coordinate System Environment Variable.
Correct




