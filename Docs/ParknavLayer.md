# ParknavLayer

``` swift
public class ParknavLayer 
```

## Initializers

### `init(destination:currentLocation:)`

``` swift
public required init(destination: CLLocationCoordinate2D,
                         currentLocation: CLLocationCoordinate2D?) 
```

## Methods

### `displayOnMap(_:shapeCollection:)`

Display the layer on the map

``` swift
public func displayOnMap(_ mapView: MGLMapView, shapeCollection: MGLShapeCollectionFeature) 
```

#### Parameters

  - mapView: mapView to display the layer on
  - shapeCollection: object of type MGLShapeCollectionFeature with all the geometric layer info
