CHANGELOG
================
## v0.4.2
* Added seek by seconds or percentage passing a parameter.
* Added new "timeLeft" property.

## v0.4.1
* Fixed bug at vg-src in Safari for Windows 8.
* Fixed bug with iOS screen size.
* Fixed bug in vgScrubbarcurrenttime, it wasn't updating the current time.

## v0.4.0
* Added support for IE11 fullscreen API.
* Added new callback vgChangeSource to change video source or quality.
* Added new stop method.
* Added licenses in all files.
* Fixed some issues related to $apply in progress error.
* Fixed to show icon correctly in overlay-play when a complete event is fired.

## v0.3.2
* Removed jQuery dependency.
* Added new vgSrc directivo to set by binding a video source.
* Added a new event ON_ERROR.
* Added gitignore, package.json and Gruntfile.

## v0.3.1
* Added support for minification.
* Added minified version.
* Fixed controlbar rendering on init.
* Now all plugin HTML templates are embedded in JS files (easier to deploy with bower).
* Improved fixEventOffset.

## v0.3.0
* Improved fixEventOffset.
* Now vg-theme it's not mandatory.

## v0.2.0
* Support for full screen on devices without native full screen.
* Removed `$rootScope` dependencies.
* Added `vgComplete`, `vgUpdateVolume`, `vgUpdateTime`, `vgUpdateSize`, `vgUpdateState` and `vgPlayerReady` callbacks.
* Exposed API with name **"API"** instead of **"vg"**.
* Fixed problems with stretch mode.
* Improved code quality in link functions.
* Added **this** changelog.
