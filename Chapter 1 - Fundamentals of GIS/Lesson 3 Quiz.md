# Lesson 3 Quiz
Latest Submission Grade 100%
<br/>

**Question 1 What happens when you make a layer in a map transparent?**
1 / 1 point

**Transparency allows the data from a lower layer to partially show through a higher layer.**

Transparent layers load more rapidly, making it a useful tool quickly explore data.

Transparent layers completely hide the layers beneath them from being shown on the map.

Transparent layers are only useful for aesthetic reasons during map creation.
Correct

When exploring data or laying out maps, setting some layers to be partially transparent can help you to view your data in the context of other data, including the basemap.

<br/>
<br/>

**Question 2 What should you do if you are not sure what your data layer represents?**
1 / 1 point

**Open the Item Description for the layer and view the associated metadata.**

Open the layer’s Attribute Table and read the short descriptions of the data’s attributes.

Assume that the data uses a standard system of symbology, for example water displayed as blue and roads as black.

Research the numbering system online.
Correct

Viewing the attached metadata is the best first step to learn more about a dataset.

<br/>
<br/>

**Question 3 What are the potential ways to change the symbology of a map layer?**
1 / 1 point

**Double click on the line representing the data in the table of contents, or open symbology under layer properties.**

Go into the preferences menu of ArcGIS to change the colors for all layers or edit the symbology in ArcCatalog.

Export the map and use a third party program to make color changes.

None of the above.
Correct

Symbology is a property of layers loaded into ArcMap, so it is set directly on the layer.



<br/>
<br/>

**Question 4 Why is scale dependent rendering helpful? Select all that apply.**
1 / 1 point

**Scale dependent rendering is useful to show specific items when the map is zoomed out to cover a large area.**
Correct

Normally it is useful to hide small items when zoomed out to keep the display uncluttered.

**Scale dependent rendering allows the user to only see data that is relevant at the current map scale.**
Correct

Scale dependent rendering allows the user control over what layers are displayed at which scale. This allows the user flexible control over what they see.

Normally data is lost when the user scrolls too far in, or out of the map, scale dependent rendering keeps the data intact.

Scale dependent rendering can improve the accuracy of some geospatial calculations performed by ArcGIS

<br/>
<br/>

**Question 5 How do features relate to records in an attribute table?**
1 / 1 point

Each column in an attribute table, name, length, ID, has a feature associated with it.

**Each record in an attribute table has a feature associated with it that displays the visual representation of data contained within the table.**

Some records have features associated with them to display visual data contained within the record.

Some features have records associated with them to display additional information.
Correct

Each record in an attribute table for a feature class has a feature associated with it and each feature has a record.


<br/>
<br/>

**Question 6 What does the select by attributes tool do?**
1 / 1 point

The select by attributes tool manipulates the data within a layer based on what the user enters.

Select by attributes is only used in cartography to change the display of a final map product.

It connects to an external database.

**It allows the user to enter a query in order to create a selection based on specific data in a feature class.**
Correct

This is incredibly useful when you need to work only with data that exhibits a certain property or characteristic!
<br/>
<br/>

**Question 7 Which of the following query clauses would match attributes of the city names “New York” and “Newbury” in an attribute table if they were in a field called “city_name”?**
1 / 1 point

city_name = ‘New’

**city_name Like ‘New%’**

city_name = ‘Newbury’

city_name Like ‘New York’

city_name Like ‘New’
Correct

This answer correctly specifies the field, the Like operator, a part of the text to match against the attributes, and a wildcard operator that allows for matching against more, currently unknown characters.




