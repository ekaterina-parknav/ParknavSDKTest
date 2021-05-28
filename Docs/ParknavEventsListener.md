# ParknavEventsListener

``` swift
public protocol ParknavEventsListener 
```

## Requirements

### shouldReroute(from:​)

``` swift
func shouldReroute(from location: CLLocation) -> Bool
```

### navigationExit(\_:​)

``` swift
func navigationExit(_ navigationObject: ParknavNavigationObject)
```

### didChangeRoute(\_:​)

``` swift
func didChangeRoute(_ route: Route)
```

### didArriveToParking(\_:​)

``` swift
func didArriveToParking(_ waipoint: Waypoint) -> Bool
```
