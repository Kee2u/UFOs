# UFOs
## Overview of Project
In this module, I built a table displaying UFO sighting data. This was stored in a JavaScript array. I added filters to make this table fully dynamic and customized it with Bootstrap.

## Results
You can filter the table by date, city, country, state and/or shape of the UFO sighted. </br></br> Here is an image of the unfiltered table: </br>

### Filter by one field
If you want to filter it by one field  (for example - date), type in the date in the date field and hit enter. </br> 
<img src = "https://github.com/Kee2u/UFOs/blob/main/static/images/filterbydate.PNG?raw=true">

### Filter by multiple fields
If you want to filter the table by any additional fields, type in the data in the required fields and hit enter. </br>
<img src = "https://github.com/Kee2u/UFOs/blob/main/static/images/filterbydateandcity.PNG?raw=true">

### Clear filters
To clear the filters, delete the text in all the inputs and hit enter.
<img src = "https://github.com/Kee2u/UFOs/blob/main/static/images/UnfilteredData.PNG?raw=true">

## Summary
One drawback of this design is that you need to manually delete all the filters in order to get the original table. </br> </br> I can improve this by adding a clear fields button to remove the filters. </br> </br> Another improvement I can make is removing case sensitivity by converting the comparison strings to uppercase. Here is the code I can use to achieve it:
> filteredData = filteredData.filter(row => row[Fid].toUpperCase() === Fval.toUpperCase());
