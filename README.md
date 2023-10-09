Baby's first Angular Project 
For D280 PA
A. Ident SVG map of the world
        mine is from https://innovsandbox.space/img/world-map.svg
B. Display six info from GeoNames or Worldbank API
    country name, capitol, region, income level, two properties of your choice
C. Assign the map comp to the default URL using routing
D. Create An Html layout with TWO columns, one for the map, one for the information from the API
E. Convert the SVG to interactive angular comp by connecting all the path tagsto mouse event handlers so each path is rec and transmitted to the parent comp hosting the map if a mouse event occurs
F. Generate an API service that uses the built in HTTP to make calls
    one method that acceps a country name input, returns additional info
    one method that triggers the api cal when a country is selected and set a local var to receive the info about the country for display in the right column of the html page