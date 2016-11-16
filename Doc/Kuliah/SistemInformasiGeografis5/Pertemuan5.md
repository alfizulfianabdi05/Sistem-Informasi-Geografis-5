In this discussion I will say little about ESRI shapefile or data that is retrieved ESRI geospatial vector geospatial data. Also I would be a little explain explanation explanation along with a tutorial that may help fellow colleagues. ESRI itself is like a vendor companies that are in geographic information systems.
We already know a file shapefile is a file that contains data about the layout of the earth, shapefile itself has supplied many examples such as those provided by ESRI but we do not know how to create shapefiles itself, by because it is here we will review how to make these shapefiles.

Here is a command in python that is used to create a shapefile:
1. Import Shapefile >>
2. >> a = shapefile.Writer (param)
Param in this writer shows shapetype what will kitabuat example, polygon, polyline and point.
3. >> a.point (x, y) Or, >> a.poly ([x, y], [v, w])
This command is used if it will make shp file.
4. >> a.field ( 'name', 'typedata', '90')
This command is used if it will make dbf file.
     >> A.record ( 'content')
This command is used to fill the dbf file.
5. >> a.shp ( 'namafile.shp') >> save ( 'filename')
Command to save the file.
