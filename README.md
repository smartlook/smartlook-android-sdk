# Smartlook Android SDK

The documentation for Android SDK can be found at https://smartlook.github.io/docs/sdk/android/

This repository serves as an issue tracker.

# Changelog
All notable changes to this project will be documented here.

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

