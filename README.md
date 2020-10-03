# turf.dart

A [turf.js](https://github.com/Turfjs/turf)-like geospatial analysis library working with GeoJSON, written in pure Dart.

This includes a fully [RFC 7946](https://tools.ietf.org/html/rfc7946)-compliant object-representation and serialization for GeoJSON.

Most of the implementation is a direct translation from [turf.js](https://github.com/Turfjs/turf).

## Components

### Measurement
- [ ] along
- [ ] area
- [ ] bbox
- [ ] bboxPolygon
- [x] [bearing](https://github.com/FranzImsch/turf_dart/blob/master/lib/bearing.dart)
- [ ] center
- [ ] centerOfMass
- [ ] centroid
- [x] [destination](https://github.com/FranzImsch/turf_dart/blob/master/lib/destination.dart)
- [x] [distance](https://github.com/FranzImsch/turf_dart/blob/master/lib/distance.dart)
- [ ] envelope
- [ ] length
- [x] (midpoint)[https://github.com/FranzImsch/turf_dart/blob/master/lib/midpoint.dart]
- [ ] pointOnFeature
- [ ] polygonTangents
- [ ] pointToLineDistance
- [ ] rhumbBearing
- [ ] rhumbDestination
- [ ] rhumbDistance
- [ ] square
- [ ] greatCircle

### Coordinate Mutation
- [ ] cleanCoords
- [ ] flip
- [ ] rewind
- [ ] round
- [ ] truncate

### Transformation
- [ ] bboxClip
- [ ] bezierSpline
- [ ] buffer
- [ ] circle
- [ ] clone
- [ ] concave
- [ ] convex
- [ ] difference
- [ ] dissolve
- [ ] intersect
- [ ] lineOffset
- [ ] simplify
- [ ] tesselate
- [ ] transformRotate
- [ ] transformTranslate
- [ ] transformScale
- [ ] union
- [ ] voronoi

### Feature Conversion
- [ ] combine
- [ ] explode
- [ ] flatten
- [ ] lineToPolygon
- [ ] polygonize
- [ ] polygonToLine

### MISC
- [ ] kinks
- [ ] lineArc
- [ ] lineChunk
- [ ] lineIntersect
- [ ] lineOverlap
- [ ] lineSegment
- [ ] lineSlice
- [ ] lineSliceAlong
- [ ] lineSplit
- [ ] mask
- [ ] nearestPointOnLine
- [ ] sector
- [ ] shortestPath
- [ ] unkinkPolygon

### Helper
- [ ] featureCollection
- [ ] feature
- [ ] geometryCollection
- [ ] lineString
- [ ] multiLineString
- [ ] multiPoint
- [ ] multiPolygon
- [ ] point
- [ ] polygon

### Random
- [ ] randomPosition
- [ ] randomPoint
- [ ] randomLineString
- [ ] randomPolygon

### Data
- [ ] sample

### Interpolation
- [ ] interpolate
- [ ] isobands
- [ ] isolines
- [ ] planepoint
- [ ] tin

### Joins
- [ ] pointsWithinPolygon
- [ ] tag

### Grids
- [ ] hexGrid
- [ ] pointGrid
- [ ] squareGrid
- [ ] triangleGrid

### Classification
- [x] [nearestPoint](https://github.com/FranzImsch/turf_dart/blob/master/lib/nearest_point.dart)

### Aggregation
- [ ] collect
- [ ] clustersDbscan
- [ ] clustersKmeans

### META
- [ ] coordAll
- [ ] coordEach
- [ ] coordReduce
- [ ] featureEach
- [ ] featureReduce
- [ ] flattenEach
- [ ] flattenReduce
- [ ] getCoord
- [ ] getCoords
- [ ] getGeom
- [ ] getType
- [ ] geomEach
- [ ] geomReduce
- [ ] propEach
- [ ] propReduce
- [ ] segmentEach
- [ ] segmentReduce
- [ ] getCluster
- [ ] clusterEach
- [ ] clusterReduce

### Assertions
- [ ] collectionOf
- [ ] containsNumber
- [ ] geojsonType
- [ ] featureOf

### Booleans
- [ ] booleanClockwise
- [ ] booleanContains
- [ ] booleanCrosses
- [ ] booleanDisjoint
- [ ] booleanEqual
- [ ] booleanOverlap
- [ ] booleanParallel
- [ ] booleanPointInPolygon
- [ ] booleanPointOnLine
- [ ] booleanWithin

### Unit Conversion
- [ ] bearingToAzimuth
- [ ] convertArea
- [ ] convertLength
- [ ] degreesToRadians
- [ ] lengthToRadians
- [ ] lengthToDegrees
- [ ] radiansToLength
- [ ] radiansToDegrees
- [ ] toMercator
- [ ] toWgs84
