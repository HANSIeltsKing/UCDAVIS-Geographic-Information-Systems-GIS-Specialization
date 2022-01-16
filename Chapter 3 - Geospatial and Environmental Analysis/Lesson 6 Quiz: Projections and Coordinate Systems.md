# Lesson 6: Projections and Coordinate Systems
Latest Submission Grade 100%
<br/>

**Question 1 Which of the following attributes of spatial
data are commonly distorted by projection of vector data? Check all that apply.**
3 / 3 points

**Scale.**
Correct

Scale is one of several attributes of all spatial data that is distorted
through projection.

**Shape.**
Correct

Shape is one of several attributes of all spatial data that is distorted through projection. 

Color/Attribute
Value.

**Distance.**
Correct

Distance is one of several attributes of all spatial data that is distorted through projection. 

<br/>
<br/>

**Question 2 What
is one practical reason to understand datums with a desktop GIS?** 
1 / 1 point

Datums are a mathematical construct that ArcGIS handles, the user never needs to be aware of them.

**Coordinates in different, but similar, datums
can be a significant distance apart.** 

Datums are only used for three-dimensional
information and only needed if your project contains elevation data. 

Datums were standardized in 1927, only projection systems vary in modern datasets.
Correct

Data stored in  different datums can contain identical decimal
degree coordinates that represent different locations on the planet!


<br/>
<br/>

**Question 3 In a cylindrical projection, how does the distance from the standard parallel affect distortion?**
1 / 1 point

Distortion increases in the northern hemisphere and down in the southern with relation to the standard parallel. 

Distortion decreases the farther a point is from the standard parallel.

**Distortion increases the farther a point is from the standard parallel.**

There is no change in distortion relating to the distance from the standard parallel.
Correct


<br/>
<br/>

**Question 4 In a geographic coordinate system (GCS) lines of ___ represents the X coordinate and lines of ___ represent the Y coordinate.**
1 / 1 point

**longitude, latitude**

symmetry, latitude

latitude, longitude

parallels, meridians
Correct


<br/>
<br/>

**Question 5 What are the advantages of the Universal Transverse Mercator (UTM) projection system? Check all that apply.**
2 / 2 points

**UTM is usable across the globe, so becoming familiar with UTM allows the user to work in multiple areas.**
Correct

UTM is a strong system because it can be translated to anywhere on the globe without having to learn a new projection system.

A UTM projection has optimized distortion that is equal across the globe.

**UTM is broken up into sections, and for points
within a section is highly accurate.**
Correct

One of the strengths of UTM is its accuracy within its regions and the fact that there is a reasonably accurate region for each part of the globe.

UTM is a conical projection that has low error.


<br/>
<br/>

**Question 6 What is the difference between the Project tool and the Define Projection tool in ArcGIS?**
1 / 1 point

**The Project tool reprojects the data in a dataset from one coordinate system to another and the Define Projection tool specifies the projection the data is currently in without modifying the underlying data.**

The Project tool is for starting a new project document and the Define Projection tool is for looking up projection definitions.

The Define Projection tool is for creating new projections and the Project tool is for displaying data in a projection.

The Define Projection tool changes the projection of the map document display and the Project tool performs datum conversion calculations on datasets.
Correct

The Project tool changes the underlying structure of the data and transforms the coordinates. Think of it as re-projecting already projected data. The Define Projection tool tells ArcGIS what projection a dataset is already in, but doesn’t reproject the data.



