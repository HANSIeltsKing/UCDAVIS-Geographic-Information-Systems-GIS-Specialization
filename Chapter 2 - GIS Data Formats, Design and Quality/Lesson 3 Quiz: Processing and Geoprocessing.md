# Lesson 3 Quiz: Processing and Geoprocessing
Latest Submission Grade 100%
<br/>

**Question 1 When is it advantageous to
use the project tool to rewrite the features of a data layer into a new
projection?**     
1 / 1 point

**When you have layers of
data with different projection types.**    

To adjust how the data is
displayed on the screen because the scale is wrong.    

When the data does not have
the necessary level of precision for the current task.    

When the data has errors.    
Correct

It can be helpful
to have all layers in the same projection format and the projection tool is a
way to accomplish this. If you don’t keep all of your data in the same
projection, ArcMap will reproject it behind the scenes because it needs the
coordinates to be in the same coordinate system.    



<br/>
<br/>

**Question 2 Which of the following
statements best describe the Geoprocessing tool set in ArcGIS?**    
1 / 1 point

Geoprocessing takes a
projection and displays it on the users screen.    

Geoprocessing tools communicate with ArcCatalog to manage available data types 

**Geoprocessing tools let the user run functions that transform or analyze their data through one or many operations on the data.** 

Geoprocessing is the
interface which programmers use to update ArcGIS.    
Correct

Geoprocessing
encompasses a wide variety of tools in ArcGIS and let the user transform their
data in effective ways.     


<br/>
<br/>

**Question 3 What does the Intersect
Tool do?**    
1 / 1 point

The Intersect Tool outputs
the differences between two layers.     

**The Intersect Tool returns the common area of the layers provided to it as a new layer.**

The Intersect Tool returns
the common area between the selected layer set and the basemap    

The Intersect Tool creates a join for two or more layers and outputs the combined layer. 
Correct

The Intersect Tool does indeed return the common area of layers provided to it as as new layer.




<br/>
<br/>

**Question 4 Given the following data table, named “land_ownership” and query, check all records that would be returned.** 
![1](https://user-images.githubusercontent.com/96668549/149662747-3c04f5f4-cc8b-4db9-a697-a4f99233d9df.PNG)

**Query:** *SELECT * FROM land_ownership WHERE [land_type_id] = 1 AND ([land_owner_id]
= 2 OR [land_owner_name] = ’Public_Federal’)*

location_id: 1    

**location_id: 2**    
Correct

This record would be
returned. The statement SELECT * FROM land_ownership
WHERE [land_type_id] = 1 evaluates as TRUE
and the second half of the statement AND ([land_owner_id]
= 2 OR [land_owner_name] = ’Public_Federal’) also evaluates as TRUE because the land_owner_name is Public_Federal. This record evaluates as TRUE AND
TRUE resulting in the record being returned.    

location_id: 3

**location_id: 4**
Correct

This record would be returned. The statement SELECT * FROM land_ownership WHERE [land_type_id] = 1 evaluates as TRUE and the second half of the statement AND([land_owner_id] = 2 OR [land_owner_name] = ’Public_Federal’)  also evaluates as TRUE. The query for this records evaluates to TRUE AND TRUE resulting in the record being returned.

location_id: 5    

<br/>
<br/>

**Question 5 Which of the following best
describes the effect of the following Python Code:** 

*employeeInitial =
!employeeInitial!.upper()*    
1 / 1 point

Creates a new field and
populates it with employeeInitial set to upper case.    

**Transforms the content of the
field employeeInitial to upper case and stores it back in employeeInitial,
overwriting the previous data.**    

Moves employeeInitial to be
the first column in the data table.    

Sorts employeeInitial
alphabetically so the upper half of the table begins with the letter “A”.     
Correct

The effect of this would be transforming the content to upper case storing it back in and overwriting.




<br/>
<br/>


**Question 6 What does the Interactive
Selection Method Option: Add to Current Selection do?**    
1 / 1 point

Adds the currently highlighted feature to your
selection.

**Changes the function of the
Interactive Selection tool to add features selected to the current section,
rather than replace the old selection with a new one.** 

Allows the user to input a
query to return valid features to add to the current selection.     

Creates a new layer using
the currently selected features.     
Correct

The Add to Current
Selection option modifies the Interactive Selection Tool to add new selections
to the current selection, rather than creating a new selection.     
