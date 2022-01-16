# Lesson 6 Quiz
Latest Submission Grade 100%
<br/>

**Question 1 Why
might we fill a DEM?** 
1 / 1 point

**DEMs have small artifacts in the landscape
called sinks that result in flow accumulation incorrectly stopping.**

DEM data is incomplete so we need to add values
to cells that are missing data.

The Flow Direction tool can’t process locations
with equal hydrologic slope, so we add fill to equal locations to make one the
clear outflow for each cell.

We fill a DEM so that we can better visualize
the landscape.
Correct

Since DEMs are models, the sampling of the landscape can sometimes result in imperfections large enough to affect the processing. Sinks or holes are one such imperfection, and they need to be resolved before we can get accurate flow direction from a DEM. For more information, review video Watershed Processing.


<br/>
<br/>

**Question 2 What
does a cell in a flow accumulation raster represent?**
1 / 1 point

**The number of upstream cells**

The direction the cell flows

The identity of the streamline on which the cell
is located.

The elevation of the cell
Correct

A flow accumulation raster counts the number of
upstream cells in each cell, with values accumulating as you move down the flow
accumulation raster. For more information, review video DEM for Hydrology.


<br/>
<br/>

**Question 3 Which of the following could be considered a suitability
analysis? Check all that apply.**
1 / 1 point

**Assessing the best location for a new business
based upon neighborhood demographics, available access to supply routes, zoning
laws, local tax incentives, and other variables affecting business success.**
Correct

This task has the hallmarks of a suitability
analysis – looking for a location for a purposed based on a combination of
numerous criteria. For more information, review video Suitability Analysis.

Making a map of home prices of people who make
below average income.

Creating a raster-representing slope for a
region of interest.

**Determining where to locate a fire lookout using
visibility (Viewshed) to surrounding areas, fire severity, access road availability
and distance from other lookouts.**
Correct

This
task has the hallmarks of a suitability analysis – looking for a location for a
purposed based on a combination of numerous criteria. For more information, review video Suitability Analysis.



<br/>
<br/>

**Question 4 What does the Reclassify tool do when used as part of a suitability analysis?**
1 / 1 point

Changes ArcGIS from working on one variable to another variable in the suitability process.

Corrects errors in a continuous raster surface by filling them in with a specified value.

**Rewrites the underlying values in a raster in a
way that turns them into scores instead of raw values.**

Combines rasters into a final, scored surface.
Correct

While the raw values of a distance raster, for
example, aren’t comparable to another raster, we can rewrite the raster values
with the Reclassify tools so that they can be used together. For more information, review video Demo: Suitability Analysis.



