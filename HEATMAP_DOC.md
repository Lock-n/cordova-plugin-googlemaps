# Heatmap class

_This class extends [BaseClass](https://github.com/mapsplugin/cordova-plugin-googlemaps-doc/blob/master/v2.6.0/class/BaseClass/README.md)_.

## Contents

  - <a href="#overview">Overview</a>
    - <a href="#create-a-heatmap">Create a heatmap</a>
    - <a href="#listen-click-event">Click event</a>
    - <a href="#bindto-method">bindTo() method</a>
  - <a href="#api-reference">API Reference</a>

------------

## Overview


### Create a heatmap

```js
var map = plugin.google.maps.Map.getMap(mapDiv);

// Datapoints
var data = [
    /*[lat, lng]*/
    [-10.5578, 10.5578],
    [-11.5578, 11.5578],
    [-12.5578, 12.5578]
    /*[-13, 13], ...*/
];

var heatmap = map.addHeatmap({
  data: data,
  radius: 20,
  opacity: 0.7
});
```

#### setData() method

Use the `setData()` method to reset the heatmap data.

---------------------------------------------------------------

#### setRadius() method

Use the `setRadius()` method to reset the heatmap radius.

---------------------------------------------------------------

#### setOpacity() method

Use the `setOpacity()` method to reset the heatmap opacity.
