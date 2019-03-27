sources:
Micah Stubbs
http://bl.ocks.org/micahstubbs/8e15870eb432a21f0bc4d3d527b2d14f



###############################################
3-19-19
-all 5 files: 2 js, 1 html, 1 json, 1 tsv
-Open index.html in firefox browser. check for any  errors, as there shouldnt be any 

-next step, convert the d3 function of tsv (tab seperated file) to read from our tsv data set

-figure out how to add the extra columns into our index.html to print population, fertility, life_expectancy

-figure out how to do a "scroll" menu for years, which changes viewing country data

##############################################
3-20-19


-was able to do the following:


+created a tsv (tab seperated file) from our desired dataset, with only Year 1960 statistics (1960_Demo.tsv)
+within the 1960_demo.tsv, countrycode column was renamed to "id" and Population column renamed to "population" (note:P to p)
+changed the index.html to read from country_population.tsv to 1960_Demo.tsv
+ran the index.html in firefox, displayed the population stats as desired
##################################################
3-27-19

-added 3 buttons to color code the countries by: population, fertility rate, and life expectancy
