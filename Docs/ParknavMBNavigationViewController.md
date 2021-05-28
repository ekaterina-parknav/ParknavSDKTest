# ParknavMBNavigationViewController

``` swift
public class ParknavMBNavigationViewController: NavigationViewController 
```

## Inheritance

`MGLMapViewDelegate`, `NavigationViewController`, [`ParknavMBNavigationDisplayLogic`](/ParknavMBNavigationDisplayLogic)

## Initializers

### `init?(coder:)`

``` swift
required public init?(coder aDecoder: NSCoder) 
```

### `init(for:directions:styles:locationManager:eventsListener:locationHistoryService:parknavRouteOptions:)`

``` swift
public init(for route: Route, directions: Directions, styles: [Style]?, locationManager: NavigationLocationManager?, eventsListener: ParknavEventsListener?, locationHistoryService: LocationHistoryService, parknavRouteOptions: ParknavRouteOptions) 
```

## Methods

### `prepare(for:sender:)`

``` swift
override public func prepare(for segue: UIStoryboardSegue, sender: Any?) 
```

### `viewDidLoad()`

``` swift
override public func viewDidLoad() 
```

### `viewDidAppear(_:)`

``` swift
public override func viewDidAppear(_ animated: Bool) 
```

### `viewWillDisappear(_:)`

``` swift
public override func viewWillDisappear(_ animated: Bool) 
```

### `viewDidLayoutSubviews()`

``` swift
public override func viewDidLayoutSubviews() 
```

### `mapView(_:imageFor:)`

``` swift
public func mapView(_ mapView: MGLMapView, imageFor annotation: MGLAnnotation) -> MGLAnnotationImage? 
```
