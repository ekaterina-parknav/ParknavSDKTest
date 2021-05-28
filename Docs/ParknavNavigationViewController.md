# ParknavNavigationViewController

``` swift
public class ParknavNavigationViewController: UIViewController, ParknavNavigationDisplayLogic 
```

## Inheritance

[`ParknavNavigationDisplayLogic`](/ParknavNavigationDisplayLogic), `UIViewController`

## Properties

### `delegate`

``` swift
public var delegate: ParknavEventsListener? 
```

### `preferredStatusBarStyle`

``` swift
public override var preferredStatusBarStyle: UIStatusBarStyle 
```

## Methods

### `presentFrom(_:options:)`

``` swift
class public func presentFrom(_ viewController: UIViewController,
                                  options: ParknavRouteOptions?) -> ParknavNavigationViewController? 
```

### `showFrom(_:options:)`

``` swift
class public func showFrom(_ viewController: UIViewController,
                               options: ParknavRouteOptions?) -> ParknavNavigationViewController? 
```

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

### `viewWillTransition(to:with:)`

``` swift
public override func viewWillTransition(to size: CGSize, with coordinator: UIViewControllerTransitionCoordinator) 
```
