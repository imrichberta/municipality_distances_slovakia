# Distance matrix between municipalities 
A simple script to create the matrix. Distances are in seconds by car, using the maximal speed limit on every type of road.

## Constitution
Python 3.8.2  
OSMNX package

## OSMNX Installation
`$ pip install osmnx`  

`$ conda install osmnx` did not work for me 



OSM road network is obtained through osmnx package. It takes a few minutes and several gigabytes of RAM to load the whole road network.

The script uses a list of Slovakian municipalitis with geographical coordinates of their centers. OSMNX package takes the two coordinates, finds the closest point on the road network for each coordinate pair, and find the shortest path between the two network points. 
