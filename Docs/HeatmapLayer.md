# HeatmapLayer

``` swift
public class HeatmapLayer: ParknavLayer 
```

## Inheritance

[`ParknavLayer`](/ParknavLayer)

## Initializers

### `init(destination:currentLocation:spotType:radius:minProb:maxProb:minLength:maxLength:)`

``` swift
public init(destination: CLLocationCoordinate2D,
                currentLocation: CLLocationCoordinate2D?,
                spotType: ParknavRouteOptions.SpotType? = ParknavRouteOptions.SpotType.all,
                radius: Int? = 1000,
                minProb: Double? = 0,
                maxProb: Double? = 1,
                minLength: Int? = nil,
                maxLength: Int? = nil) 
```

### `init(destination:currentLocation:)`

``` swift
public required init(destination: CLLocationCoordinate2D, currentLocation: CLLocationCoordinate2D?) 
```

## Methods

### `displayOnMap(_:shapeCollection:)`

``` swift
public override func displayOnMap(_ mapView: MGLMapView, shapeCollection: MGLShapeCollectionFeature) 
```
