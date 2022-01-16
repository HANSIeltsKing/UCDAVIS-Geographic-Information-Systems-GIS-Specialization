# Lesson 4: Surfaces and the Third Dimension
Latest Submission Grade 100%
<br/>

**Question 1 Which of the following can be gained from interpolation of data to a TIN? Check all that apply.**
2 / 2 points

A new dataset with higher resolution, and additional precision.

**The ability to make new or different prediction
with a dataset.** 
Correct

A three-dimensional rendering with elevation information from a two-dimensional raster without elevation information.

**A
new dataset with higher resolution, but no additional precision.** 
Correct


<br/>
<br/>

**Question 2 Which of the following rasters would be easily translatable to interpolated 3-D models? Check all that apply.**
2 / 2 points

A land use type raster.

**A population raster.**
Correct

A population raster does not contain height information, however it is possible to display the data in three dimensions. In this case, the Z (height) value would be the population number, rather than the physical height of a location.

A categorical fire hazard zone raster.

**A digital elevation model (DEM).**
Correct

A DEM inherently contains Z (height) values and thus is easily transformed into a 3-D representation.


<br/>
<br/>

**Question 3 What is the different between a fishnet and a Voronoi polygon as a method of zone creation?**
1 / 1 point

**In a GIS a Voronoi polygon creates zones with respect to specific data points. A fishnet create zones without respect to data points.**

Voronoi polygons are the result of applying fishnet zones to a TIN.

A fishnet creates zones using rectangles based on a central point of the data and scales the rectangle size based on the value within each cell. A Voronoi polygon is based on the dataset’s datum, not the data of the dataset.

A fishnet
is created by Voronoi polygons.
Correct

<br/>
<br/>

**Question 4 Which of the following are reasons that TINS are
a good choice for interpolation? Check all that apply.**
3 / 3 points

**TINs are simple compared to other methods such
as Inverse Distance Weighting and Splines.**
Correct

**TINs perform well with scattered values that were sampled empirically.**
Correct

TINs can be stored and treated the same way as
rasters in ArcGIS.

**TINs connect values together.**
Correct




<br/>
<br/>

**Question 5 As described in the lecture “TINs in Action” there is a relationship between a TIN and the Thiessen/Voronoi polygons created by the Create Thiessen Polygon tool. How are the two related?** 
1 / 1 point

Voronoi polygons are created from TINs, by connecting the centers of each triangle in the TIN to all neighboring triangle centers.

TINs and Voronoi polygons are both based on the
spline interpolation method.

**TINs are created from Voronoi polygons by connecting the central points in each Voronoi polygon to all neighboring polygon centers.**

Voronoi polygons are joined to TINs to transfer attributes.
Correct

While ArcGIS won’t add a layer for the Voronoi polygons used to create a TIN, in the background, that is a primary method for triangulation.




<br/>
<br/>

**Question 6 What
is the importance of the Current Z Value
tool?**
1 / 1 point

The Current
Z Value tool sets the default height of the camera when the user views a
layer in 3-D.

**The
Current Z Value tool sets what
default Z value points added to a map will have.**

The Current
Z Value tool sets the definition of sea level, or the zero elevation for
each map.

The
Current Z Value tool is like select
by location, but for 3-D applications.
Correct

The Current Z Value tool sets the
default value when digitizing 3-D data.



