# Lesson 3: Working with Rasters
Latest Submission Grade 100%
<br/>

**Question 1 When using raster data, what is the difference between a lossless and lossy file format?**
1 / 1 point

All data formats that take the data outside of ArcGIS are lossy, formats that keep the data within ArcGIS are lossless.

Lossless formats protect the user from making
errors with their data, such as choosing a mismatched projection type. Lossy
formats allow the user more freedom, but do not protect against user errors.    

Lossy formats are not used in ArcGIS, lossless
formats are standard. 

**Lossless formats, such as TIF, do not change the data in any way. Lossy formats, like JPEG, compress the data and cause a loss of precision.** 
Correct

Lossy formats have a loss of value precision
due to compression, while lossless formats do not lose precision, but are
usually much larger in size.

<br/>
<br/>

**Question 2 Choose the resampling methods that are most suitable for use for discrete/categorical rasters (such as land use) when changing cell sizes or alignment. Choose all that apply.**
2 / 2 points

**Majority**    
Correct

Majority does not perform
interpolation and minimizes changes to the underlying data. As a result, it can
be used for discrete data.    

Cubic Convolution    

Bilinear Interpolation    

**Nearest Neighbor**    
Correct

The Nearest Neighbor method
minimizes modifications to the underlying data    


<br/>
<br/>

**Question 3 What information does an aspect raster
display?** 
1 / 1 point

Aspect
raster display the slope of each cell.

An aspect raster displays two pieces of information, slope and magnitude of the slope.

**An aspect raster displays the direction that a slope faces on a 360 degree compass for each raster cell based on its neighbors.**

An aspect raster is another word for a DEM
(digital elevation model). 
Correct

An aspect raster does display the direction that a slope faces on a 360 degree compass for each raster cell based on its neighbors.

<br/>
<br/>

**Question 4 What
is the purpose of the Swipe tool?** 
1 / 1 point

The Swipe tool is used to change the symbology of one raster layer, normally from color to black and white.

**The Swipe tool allows the user to slide the cursor across the screen and switch between two rasters to display.**

Swipe allows the user to quickly delete
raster data layers. 

Swipe allows the user to quickly change a layer from raster to vector type by swiping the cursor across the screen. 
Correct

The Swipe tool allows the user to swipe their cursor across the screen and change between one of two rasters to display on a specific side of the screen.


<br/>
<br/>

**Question 5 Which of the following are possible ways to select data to extract from a raster? Check all that apply.**
3 / 3 points

**By
value.**
Correct

One can select data to extract from a raster by value.

**By
a raster mask**     
Correct

One can select data to extract from a raster by using a raster mask.

Raster data is not the correct format to
perform extractions on. To make extractions it is needed to convert to a vector
format first.    

**By
a vector mask.**    
Correct

One can select data to extract from a raster by using a vector mask.


<br/>
<br/>

**Question 6 What are the key differences between raster and vector data in terms of re-projections? Check all that apply.**
2 / 2 points

**Raster data does not have its values tied to a
shape so when a projection is done, there will be error introduced into both the
locations and values.**
Correct

Because raster data does not have its values tied to a shape, error will be introduced.

Raster
data is better than vector data if you need to re-project because raster data
is easier for the computer to manipulate. 

Vector
data has its attribute information distorted when it is re-projected.

**Vector and raster data can both be re-projected,
but it is important to be aware of the effects of doing so.**
Correct

Both data types can be projected, but
as with any operation in ArcGIS, it is important to be aware of any potential
error that will be introduced.


<br/>
<br/>

**Question 7 What
are the advantages of using the Create
Mosaic Dataset tool to combine rasters vs. loading the data as multiple
rasters in the same data frame? Check all that apply.**
2 / 2 points

The Create
Mosaic Dataset tool allows vector data to be joined to raster data with
less error than other methods of conversion.

**Using Create
Mosaic Dataset to combine rasters allows the user to perform analyses on
the data as a whole unit, rather than have to perform a separate analysis for
each raster and combine them later.**
Correct

Performing an analysis on data from multiple, non-overlapping rasters is challenging and in most cases it is preferable to combine them first.

**The
color ramp for each raster is likely to be different if they have different
minimum and maximum values. Using the Create
Mosaic Dataset tool to combine them together will ensure that the data is
displayed in a uniform manner.**    
Correct

Different rasters with different
minimum and maximum values will have different stretches on their color ramps which
can be misleading if they are being displayed as one, contiguous section of
data. 

It is not advantageous to use Create Mosaic Dataset, unless you plan to export the data, in which case it will increase the accuracy of the data.
