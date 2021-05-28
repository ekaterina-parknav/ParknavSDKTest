# ParknavRouteOptions

``` swift
public struct ParknavRouteOptions 
```

## Initializers

### `init()`

``` swift
public init() 
```

## Properties

### `instance`

``` swift
public static var instance 
```

### `destination`

``` swift
public var destination: CLLocationCoordinate2D?
```

### `spotType`

``` swift
public var spotType: SpotType = .all
```

### `proximity`

``` swift
public var proximity: Proximity = .close
```

### `lang`

``` swift
public var lang: Lang?
```

### `localeID`

``` swift
public var localeID: String = Locale.current.identifier
```

### `navigateToDestination`

``` swift
public var navigateToDestination: Bool = true
```

### `maxPathLength`

``` swift
public var maxPathLength: Int = 1000
```

### `outputFormat`

``` swift
public var outputFormat: OutputFormat = .mapbox
```

### `previousRequestId`

``` swift
public var previousRequestId: String?
```

### `dayStyle`

``` swift
public var dayStyle: MapStyle?
```

### `nightStyle`

``` swift
public var nightStyle: MapStyle?
```

### `serverInfo`

``` swift
public var serverInfo: ServerInfo?
```

### `isSimulationEnabled`

``` swift
public var isSimulationEnabled: Bool = false
```

### `destinationReachedThreshold`

``` swift
public var destinationReachedThreshold: Double = 100
```

### `showRouteType`

``` swift
public var showRouteType: Bool = true
```

### `allowDestinationSelection`

``` swift
public var allowDestinationSelection: Bool = false
```

### `isNavigationOnly`

``` swift
public var isNavigationOnly: Bool = false
```

### `garageSupport`

``` swift
public var garageSupport: GarageSupport = .noGarages
```

### `garagesOnParkingRoute`

``` swift
public var garagesOnParkingRoute: Bool = false
```

### `garageRadius`

``` swift
public var garageRadius: Int = ParknavConstans.Layers.radius
```

### `routeSource`

``` swift
public var routeSource: RouteSource = .prob
```

### `isFullscreen`

``` swift
public var isFullscreen = true
```
