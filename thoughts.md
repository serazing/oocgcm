http://earthpy.org/dask.html


arrays in the grid 
 - numpy
 - dask from numpy
 - dask from dataset
 - xarray ? 

NB requires caching functionality

array to process : 
 - pas de restruction sur le type

 - pbm xarray pas de map_overlap...


pbm chunks inside should match chunk in/out

xarray in/out + numpy grid : très slow.


sur le roll et les ghost cells dans xarray : 
https://groups.google.com/forum/#!msg/xarray/FmweMn-bDjE/zMiKkeLkDAAJ


xarray, sur la multiplication avec tab numpy.
http://stackoverflow.com/questions/35592074/value-error-in-multplying-xarray-variable-with-2d-numpy-array

mon impression : 
 - dask mur. 
 - xarray pas encore pour nous...