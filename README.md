# Smartlook Android SDK

The documentation for Android SDK can be found at https://smartlook.github.io/docs/sdk/android/

This repository serves as an issue tracker.

# Changelog
All notable changes to this project will be documented here.

## [1.4.0] - 2020-03-11

### Added
- Wireframe rendering mode
- TabItem selector identification
- OkHttp network interceptor

### Fixed
- Orientation detection problems
- WebView recording stability issues

### Changed
- Improved image downscaling == better video quality
- Smartlook API doesnt have obfuscated parameter names
- Improved selector detection
- Removed **deprecated** API methods from versions under 1.0.0

## [1.1.5] - 2019-09-17

### Fixed
- Referrer detection now stable
- Tracking of focus gain event

### Added
- Detection of ANR implemented
- New custom timed event

### Changed
- Optimized video size and bitrate so the recordings are smaller than 0,5 MB per minute

## [1.1.2] - 2019-08-20

### Fixed
- User identification now works consistently regardless of when it gets called

## [1.1.1] - 2019-08-19

### Added
- Added ability to adjust view name for "click" events
- Prepared SDK for mobile uploads

### Fixed
- Json parsing issues

## [1.1.0] - 2019-08-07

### Added
- Custom navigation events
- Added ability to not record sensitive elements in WebViews
- Automatic hiding of input elements on WebViews

### Fixed
- Fixed some minor stability issues
- Adaptive framerate is allowed only on native/React SDKs
- Fixed some FragmentDialog recording issues

## [1.0.1] - 2019-07-24

### Fixed
- Fixed some minor stability issues
- Resolved OkHttp v3 and v4 incompability issues

## [1.0.0] - 2019-07-18

### Added
- Adaptive framerate (SDK does not capture new video frames when application idle)
- View/class blacklist and whitelist for marking views as (non) sensitive
- Sensitive mode

### Changed
- API rewriten and unified with iOS API
- Timed event has event properties

### Deprecated
- Most of original API methods were deprecated

### Fixed
- Significant stability improvement
- Fixed keyboard detection
- Recording is not randomly stopping on activity change or orientation change
- Resolved OkHttp v3 and v4 incpomatibility crash
- A variety of minnor issue were fixed

## [0.9.0.2.5.7-beta] - 2019-05-23
### Changed
- New isRecording() method - you can now check if SDK is running or not
- Improved capture logic and selectors detection
- Fix of several minor issues


## [0.9.0.2.5.3-beta] - 2019-04-11
### Changed
- Possibility to use initPassive method and controll recording via start/pause methods
- Fix of cached sessions -> sometimes we created two visitors for single user
- Better lifecycle handling of the activities
- Fix of stability issues for some Huawei/Honor models


## [0.9.0.2.3.9-beta] - 2019-03-26
### Changed
- Possibility to set desired FPS in init methods
- Possibility to init SDK in the middle of the app lifecycle
- Automatic detection of activity/fragment/dialog lifecycle + duration metrics
- Fix of session length
- Better detection that keyboard is active
- Alpha functionality for form analytics -> You can now see which input was somehow problematic for the user to fill in
- Fix of several stability issues


## [0.9.0.2.1.9-beta] - 2019-02-25
### Changed
- Enhanced selector detection
- Fixed display resolution metrics
- Better functionality of pause/start methods
- Fix of several stability issues


## [0.9.0.2.1.4-beta] - 2019-01-14
### Changed
- Better detection of selectors
- Better handling of orientation events
- Minor non-critical bugfixes


## [0.9.0.2.0.8-beta] - 2019-01-14
### Changed
- Overall performance improvements
- Better handling of app's lifecycle
- Several bugfixes


## [0.9.0.2.0.2-beta] - 2019-01-08
### Changed
- Better click detection
- Several bugfixes


## [0.9.0.2.0.0-beta] - 2018-12-19
### Changed
- Multitouch detection
- Keyboard event -> shown in dashboard
- Experimental recording of native maps and MapBox
- Improvement of offline recordings
- Several bugfixes


## [0.9.0.1.8.1-beta] - 2018-11-30
### Changed
- Fixed `ArrayIndexOutOfBoundsException` bug described in issue #8.


## [0.9.0.1.7.7-beta] - 2018-11-22
### Changed
- Improved click detection
- Bug fix: https://github.com/smartlook/smartlook-android-sdk/issues/8

