# ParknavAPI

``` swift
public class ParknavAPI 
```

## Methods

### `getDirections(currentLocation:currentAngle:options:)`

``` swift
public class func getDirections(currentLocation: CLLocationCoordinate2D,
                                   currentAngle: Double,
                                   options: ParknavRouteOptions) -> Future<DirectionsResponse,NSError>
```

### `getLayer(_:serverInfo:)`

``` swift
public class func getLayer(_ layer: ParknavLayer, serverInfo: ServerInfo?) -> Future<MGLShapeCollectionFeature,NSError> 
```
