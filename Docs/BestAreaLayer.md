# BestAreaLayer

``` swift
public class BestAreaLayer: ParknavLayer 
```

## Inheritance

[`ParknavLayer`](/ParknavLayer)

## Initializers

### `init(destination:currentLocation:radius:minSize:maxSize:numAreas:)`

``` swift
public init(destination: CLLocationCoordinate2D,
                currentLocation: CLLocationCoordinate2D?,
                radius: Int?,
                minSize: Int?,
                maxSize: Int?,
                numAreas: Int?) 
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
