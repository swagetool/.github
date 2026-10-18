# Swage

Swage converts CAD and GIS files between formats: DWG, DXF, MapInfo TAB,
Shapefile, GeoPackage, GeoJSON, KML and more.

Before writing, it tells you in numbers what the target format will lose:
heights, fields, text length, the coordinate system. After writing, it reads
the result back and compares it with the source, feature by feature. What
was lost is named, never silent.

- Try it: https://tryswage.com
- Contact: ask@tryswage.com

## How files are handled

Files are used only to run your job. The source file is deleted right after
it is read, the result after 24 hours. Nothing is shared with anyone.

## What you will find here

The product code is closed. When we find a bug in GDAL, LibreDWG or another
open tool while testing real files, we report it upstream with the file
numbers we measured.
