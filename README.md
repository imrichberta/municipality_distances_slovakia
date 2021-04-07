# Distance matrix between municipalities 
Simple script to create the matrix. Distances are in seconds by car, using the maximal speed limit on every type of road.

## Constitution
Python 3.8.2  
OSMNX package

## OSMNX Installation
`$ pip install osmnx`  

`$ conda install osmnx` did not work for me 



OSM road network is obtained through osmnx package. It takes a few minutes and several gigabytes of RAM to load the whole road network.
