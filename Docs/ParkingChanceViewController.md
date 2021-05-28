# ParkingChanceViewController

``` swift
public class ParkingChanceViewController: UIViewController 
```

## Inheritance

[`ParkingChanceDisplayLogic`](/ParkingChanceDisplayLogic), [`ParkingMenuViewDelegate`](/ParkingMenuViewDelegate), `UIViewController`

## Methods

### `presentFrom(_:layerRules:options:)`

Present ParkingChance view controller from another one

``` swift
class public func presentFrom(_ viewController: UIViewController, layerRules: LayerRules?, options: ParknavRouteOptions?) -> ParkingChanceViewController? 
```

#### Parameters

  - viewController: view controller from which will be presented ParkingChance
  - layerRules: object with the information about layers to be displayed
  - options: ParknavRouteOptions to use for the ParkingChance functionality

#### Returns

ParkingChanceViewController object which was presented

### `prepare(for:sender:)`

``` swift
override public func prepare(for segue: UIStoryboardSegue, sender: Any?) 
```

### `viewDidLoad()`

``` swift
override public func viewDidLoad() 
```

### `viewWillAppear(_:)`

``` swift
public override func viewWillAppear(_ animated: Bool) 
```

### `viewDidAppear(_:)`

``` swift
public override func viewDidAppear(_ animated: Bool) 
```

### `viewWillDisappear(_:)`

``` swift
public override func viewWillDisappear(_ animated: Bool) 
```
