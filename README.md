# Base To Target Locs
The Base to Target Locs is a ArcGIS Python Toolbox created to enable a drone healthcare logistics company to rapidly calculate optimal paths from a single base location to any location that falls within a specified buffer, i.e. 30km. 

Required user input parameters include:
* Geodatabase
* Feature Dataset
* Feature Class
* UTM Zone
* Name corresponding to the field name in the Feature Class
* Exact name of the base-location in the Feature Class
* Desired buffer distances

The script performs faster with fewer points, however, this script may be used with any feature class of points.
