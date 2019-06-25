# Charts Library for Flutter Web

This is the port of the [charts](https://github.com/google/charts) library to flutter_web, which was provided within [flutter_web samples](https://github.com/flutter/samples/tree/master/web/charts). Because of the relative path `../common` in its [pubspec.yaml](https://github.com/flutter/samples/blob/master/web/charts/flutter/pubspec.yaml#L18), it was not usable in other projects a dependency directly through git. 

You can use this in your Flutter Web projects as: 

```
dependencies: 
  charts_flutter:
    git:
      url: https://github.com/gazialankus/charts_flutter_web
      path: web/charts/flutter
```

Also, if you are interested in showing dash patterns in your legend, [here](https://github.com/google/charts/pull/282) I have a PR in upstream. If you want to use it now, try the [legend-dash](https://github.com/gazialankus/charts_flutter_web/tree/legend-dash) branch of this repo. 
