# Module 1 Quiz
Latest Submission Grade 100%
<br/>

**Question 1 Which
of the following spectra and wavelengths of electromagnetic radiation (light)
are useful in remote sensing applications? Check all that apply.**
1 / 1 point

**Millimeter wavelength radar**
Correct

Human visible light, thermal light, millimeter wavelength light and infrared light can all be used in remote sensing applications depending on the sensor packages and desired result.  

For more information, review video: Remote Sensing Basics.  

**Infrared light**
Correct

Human visible light, thermal light, millimeter wavelength light and infrared light can all be used in remote sensing applications depending on the sensor packages and desired result.

For more information, review video: Remote Sensing Basics.  

**Thermal light**
Correct

Human visible light, thermal light, millimeter wavelength light and infrared light can all be used in remote sensing applications depending on the sensor packages and desired result.

For more information, review video: Remote Sensing Basics.  

**Human
visible light**
Correct

Human visible light, thermal light, millimeter wavelength light and infrared light can all be used in remote sensing applications depending on the sensor packages and desired result.

For more information, review video: Remote Sensing Basics.


<br/>
<br/>

**Question 2 Which of the following are examples of remote sensing? (Select all that apply.)**
1 / 1 point

**UAV created imagery in the visible light spectrum**
Correct

UAV created imagery and satellite imagery are both forms of remote sensing regardless of the light spectrum recorded. 

For more information, review video: Remote Sensing Basics.  

Water temperature monitoring stations embedded in a river that report via cell link to a central monitoring station

Human collected soil samples

**Satellite
mounted radar imagery**
Correct

UAV created imagery and satellite imagery are both forms of remote sensing regardless of the light spectrum recorded.

For more information, review video: Remote Sensing Basics.  



<br/>
<br/>

**Question 3 In
satellite imaging, which of the following is an important reason to compare the
relative intensity of different spectra, rather than the absolute intensity?**
1 / 1 point

Different
surfaces reflect light differently and ratios of the reflections are the only
valid metric.

Light
from the sun is inconsistent in its spectrum makeup when it hits the earth’s
atmosphere, so it is important to look at the frequencies as ratios of the
other frequencies present. 

Ratios
of reflected light are not an effective measurement tool. Only the absolute
value of reflected light is accurate.

**Water
in the atmosphere absorbs at different rates depending on the spectrum and can
distort imagery. By looking at ratios of the frequencies (which have all passed
through the same amount of atmosphere), it is possible to correct for this
error.**
Correct

Water
is especially good at absorbing light in the shortwave infrared spectrum. Water
is heavily present in the earth’s atmosphere at unknown quantities for each
image. By looking at the value of each light band in to the maximum observed
value and known atmospheric characteristics, it is possible to account for the
error caused by water in the air.

For more information, see video Characteristics of Remotely Sensed Data.


<br/>
<br/>

**Question 4 If you have data that shows red, green, blue, thermal, near infrared light, how can you tell if vegetation is present, and if it is healthy? (Select all that apply.)**
1 / 1 point

**Healthy
vegetation reflect near infrared, so higher levels of near infrared light might
mean healthy vegetation is present.** 
Correct

This reflection is incorporated into NDVI as part of separating healthy vegetation from non-plant sources.

For more information, see video Normalized Difference Vegetation Index (NDVI) 

Vegetation emits thermal infrared when it is performing photosynthesis, so high levels of thermal infrared present at night indicates healthy vegetation. 

**Dying
vegetation absorbs near infrared and reflects more red than its healthy
counterpart, so a high presence of red light relative to near-infrared might
indicate dying vegetation.** 
Correct

This absorption is incorporated into NDVI to separate
healthy vegetation from non-plant sources.

For more information, see video Normalized Difference Vegetation Index (NDVI)

**Vegetation
reflects more green light then red and blue, so higher levels of green might
mean the presence of vegetation.** 
Correct

With
our eyes, we can make out objects like plants when they are green, but for
automated analysis, we’d probably still want to use NDVI. 

For more information, see video Normalized Difference Vegetation Index (NDVI)


<br/>
<br/>

**Question 5 If
you are working on a research project that requires you to identify how much
healthy vegetation is with a 10km by 10km study area, which portions of the
electromagnetic spectrum would you need imagery from, at a minimum?** 
1 / 1 point

Ultraviolet
light only

Near infrared light only

Visible and ultraviolet light

**Visible and near-Infrared light**

Visible light only
Correct

The combination of near-infrared and visible light allows for the generation of the NDVI metric, which measures vegetation’s health. For more information, see video Normalized Difference Vegetation Index (NDVI).


<br/>
<br/>

**Question 6 When
reviewing possible satellite imagery options for a project, which of the
following criteria are important? Check all that apply.**
1 / 1 point

**The
return interval**
Correct

Return interval impacts how well you can apply the imagery
to time series or longitudinal analysis. For more information, see video Modes of Acquisition.

**The
resolution**
Correct

Resolution impacts your ability to detect features on the landscape.


For more information, see video Modes of Acquisition.

**Available
bands**
Correct

The available bands determine what themes or features you can detect. 


For more information, see video Modes of Acquisition.

**Time
of image capture** 
Correct

The
time of image capture can determine which features are visible and whether or
not shadows will cover features of interest. 


For more information, see video Modes of Acquisition.




<br/>
<br/>

**Question 7 Which
of the following data products would be a good choice if you need to receive three
or more images of the same site per month? (Select all that apply.)**
1 / 1 point

Landsat

**Sentinel Program**
Correct

The European Space Agency’s Sentinel Program has a 2-3 day return time at mid-latitudes and would be a good choice for receiving data multiple times per month. For more information, see video Acquisition Platforms.

**MODIS**
Correct

MODIS
visits most places on the Earth daily and is a good choice for receiving data
multiple times per month. For more information, see video Acquisition Platforms.

NAIP 



<br/>
<br/>

**Question 8 How many 15 meter pixels fit in the same space as a 30 meter
pixel, and how does the file size of a raster at 15 meters compare to a raster
with the same bands and extent at 30 meters?**
1 / 1 point

Two 15 meter pixels per 30 meter pixel, 15 meter raster is smaller in size.

Four 15 meter pixels per 30 meter pixel, 15 meter raster is smaller in size.

Two 15 meter pixels per 30 meter pixel, 15 meter
raster is larger in size.

**Four 15 meter pixels per 30 meter pixel, 15 meter raster is larger in size**

Eight 15 meter pixels per 30 meter pixel, 15 meter raster is smaller in size.
Correct

15 meter pixels can fit as a 2x2 grid inside of 30 meter pixels and the raster itself will be larger due to having more pixels with data. For more information, see video Acquiring Imagery and Terrain Data.



<br/>
<br/>

**Question 9 If, upon loading a multispectral image into ArcMap, you
notice the coloring looks incorrect for a visible image, what is the most likely
problem and how would you attempt to correct it first?**
1 / 1 point

**The band ordering specified in the symbology needs to be corrected.**

The image is corrupted and needs to be downloaded again.

The image’s pyramids failed to build correctly
and should be rebuilt with the Build Pyramids tool. For more information, see video Working with Imagery in ArcMap.

The image isn’t licensed for use in the visible
bands and a license needs to be purchased. 
Correct

Misassignment of bands to colors by ArcIGS is the most likely choice. ArcGIS doesn’t inherently know which bands represent which colors and it’s different for every sensor, so you’ll need to find out the band ordering from whoever you obtain imagery from and then set the correct bands to the correct colors in ArcGIS. For more information, see video Working with Imagery in ArcMap.


<br/>
<br/>

**Question 10 What
is the difference between Top of Atmosphere (ToA) and Surface Reflectance (SR)
data products with remotely sensed imagery?** 
1 / 1 point

Top of Atmosphere reflectance takes into account
the effect of the atmosphere on the light as it exits and attempts to remove
that effect to simulate the light values at the surface of the earth while
Surface Reflectance is the raw data that reaches the satellite.

Top of Atmosphere reflectance is the light that
hits Earth’s atmosphere, but doesn’t penetrate and bounces off to the sensor
while Surface Reflectance is the light that goes to the surface and comes back.

Top of Atmosphere reflectance is captured by a
satellite flying through or just above the upper atmosphere while Surface
Reflectance is captured by a UAV (drone) flying within 150m of the Earth’s
surface.

**Top of Atmosphere reflectance is the raw data
that reaches the satellite while Surface Reflectance takes into account the
effect of the atmosphere on the light as it exits and attempts to remove that
effect to simulate the light values at the surface of the earth.** 
Correct

For more information, see video Acquiring Imagery and Terrain Data. 


<br/>
<br/>

**Question 11 Why are bands for individual colors (blue, for example) shown as grey in ArcMap when they’re alone without other bands from the same image? (Select all that apply.)**
1 / 1 point

**Because ArcMap doesn’t know what color the band
is**
Correct

ArcGIS doesn’t have a way to inherently know the color value, so it chooses a default. For more information, see video Working with Imagery in ArcMap.

**Because light has no inherent color that the
sensor can capture, but is instead captured as integer values representing the
intensity of that wavelength or band of light for each pixel**
Correct

Light
is not itself a color, but instead our eyes interpret colors for different
wavelengths. As a result, sensors that capture light are just capturing
intensity readings for each wavelength, and when redisplaying the light on our
screen, we need to set the color manually. ArcGIS chooses a colorless default
to reflect this. For more information, see video Working with Imagery in ArcMap.

**Because grayscale is a default color ramp to use
for continuous rasters**
Correct

Since
it’s just a set of integer values, similar to a DEM but with a different theme,
ArcGIS displays it as grayscale. For more information, see video Working with Imagery in ArcMap.

Because
ArcGIS applies a desaturation filter to the image by default until the color is
confirmed by the user 


<br/>
<br/>

**Question 12 What
is the color that will appear on your screen when the red, green, and blue
bands are all at or near their maximum intensity values?** 
1 / 1 point

Green

**White**

Brown

Black
Correct

Red, green, and blue light are the primary
colors of light, and the ones we have receptors for in our eyes. White light
results from seeing all three at once. For more information, see video Working with Imagery in ArcMap.


<br/>
<br/>

**Question 13 In a supervised classification, how does the computer determine which pixels belong to which classes (or groups)?**
1 / 1 point

It uses international data layers representing
landscape variables to determine which pixels represent which classes.

Based on statistically separating pixels so that
there is as much of a difference between groups as possible and as little
difference within groups as possible.

**It uses the pixel values of training samples
provided by the user to determine the most likely class that another pixel is
in, based on that pixel’s value.**

It randomly samples the image and determines
potential classifications of those pixels, then assigns classes to the rest
based on the first sample. The user can then adjust the classes directly.
Correct

Supervised classification is sometimes called
“trained” classification and involves a step of telling the computer about what
the pixels in each class should look like. 


