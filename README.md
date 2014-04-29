# OptaPlanner with GraphHopper precalculated routes

Open project and execute Main.main method and see the Vehicle Routing Plan problem solved by
GraphHopper and Optaplanner.

## Usage

 * Download the berlin.pbf from [geofabrik](http://download.geofabrik.de/europe/germany/berlin-latest.osm.pbf) or elsewhere
 * mvn clean install assembly:single
 * `java -jar target/*-jar-with-dependencies.jar osmreader.osm=berlin-latest.osm.pbf config=config.properties`
 * The first time will take a minute, the second time will be in a few milliseconds, depending on the matrix size

## License

This code stands under the Apache License