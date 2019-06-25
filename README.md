# Charts Library for Flutter Web

This is the port of the [charts](https://github.com/google/charts) library to flutter_web, which was provided within [flutter_web samples](https://github.com/flutter/samples/tree/master/web/charts). Because of the relative path `../common` in its [pubspec.yaml](https://github.com/flutter/samples/blob/master/web/charts/flutter/pubspec.yaml#L18), it was not usable in other projects a dependency directly through git. 

You can use this in your Flutter Web projects as: 

```
dependencies: 
  charts_flutter:
    git:
      url: https://github.com/gazialankus/charts_flutter_web
      path: web/charts/flutter
      ref: legend-dash
```

This is the branch in which showing dash pattern in legend is fixed. My PR in upstream is [here](https://github.com/google/charts/pull/282). 
