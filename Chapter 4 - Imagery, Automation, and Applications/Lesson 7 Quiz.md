# Lesson 7 Quiz
Latest Submission Grade 100%
<br/>

**Question 1 What does the Region Group tool do?**
1 / 1 point

Creates a raster of zones by randomly assigning
cells to a group.

Creates a continuous raster of new values by multiplying a raster’s values by a random group ID.

Creates a continuous raster of new values by
extracting and transforming values from a DEM

**Creates a raster of zones by giving connected
areas with the same value a numerical ID.**
Correct

Region
Group finds cells that are touching and assigns them all a new unique value to
group them together. For more information, review
video on Region Group.


<br/>
<br/>

**Question 2 Which
of the following is not a neighborhood option in Focal Statistics
(as of version 10.3)? Feel free to look at the tool if you’re not sure.**
1 / 1 point

Irregular

Wedge

Circle

**Ellipse**

Rectangle
Correct

For more information, review
video on Focal
Statistics and the Swiss Hillshade.


<br/>
<br/>

**Question 3 How does Focal Statistics factor into the Swiss Hillshade?**
1 / 1 point

Focal Statistics is used to smooth the DEM with an elliptical median filter

Focal Statistics is used to smooth the DEM with
a circular mean filter.

Focal Statistics is used to smooth a Hillshade with a circular mean filter

**Focal Statistics is used to smooth a Hillshade
with a rectangular median filter.**
Correct

Focal Statistics smooths a Hillshade by taking
the median of the values within a 4x4 window. For more information, review
video on Focal
Statistics and the Swiss Hillshade.



<br/>
<br/>

**Question 4 If
you have two categorical rasters with similar meanings and classifications, but
one has 10 classes and the other has 15, how would you best use the Reclassify tool to make them comparable?** 
1 / 1 point

Map the raster with more classes’ values to be
the same as the raster with fewer values using a Maximum Likelihood
Classification, as with imagery classification.

Map the raster with fewer classes’ values to be
the same as the raster with more values by manually entering values into a
classification table determined by comparing the metadata for each raster.

**Map the raster with more classes’ values to be
the same as the raster with fewer values using a by manually entering values
into a classification table by comparing the metadata for each raster.**

Map the raster with fewer classes’ values to be
the same as the raster with more values using a Maximum Likelihood
Classification as with imagery classification.
Correct

By reclassifying the raster with more classes to
have the same values as the raster with fewer classes, you use the extra data
available in the raster with more classes to generalize the pixels to less
specific values. Going the other way would be error-prone because you wouldn’t
have enough data to determine which more specific class to use. For more information, review video "Reclassify."



<br/>
<br/>

**Question 5 If
an area has many points when using Point Density, how might you smooth out the
density measurement to have fewer small hotspots and make a larger, general hotspot?** 
1 / 1 point

Change the search area to a rectangle

Decrease the search radius

**Increase the search radius**

Change the search area to a wedge  
Correct

When points are dense, increasing the search
area can smooth the overall density for the area. When points are sparse,
densities may disappear in the background noise when using the default
classification. For more information, review video Point Density.


