# concentration-collisions

Simply download and run the jupyter notebook concentration_collisions_builtup_areas.ipynb.

The code loads data for traffic collisions in England from 2015 to 2019. The data has been uploaded in the repository in separate files for different years. It can also be obtained from https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data

Then, it loads geodataframes cointaining hexagonal grids that provide full coverage of each English built-up area with population size greater than 200,000. The hexagonal grids have been uploaded in the repository in a file called 'Hexagons_cities_with_roadway_length.geojson'.

The number of serious and fatal traffic collisions in each hexagonal grid cell are counted. The hexagonal grid cells have an area of 50 ha.

Finally, the Gini index, Moran's I and Gini correlation corresponding to each built-up area are computed. A different way of aggregating the data into geographical units could lead to different values for these metrics.
