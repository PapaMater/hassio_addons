# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.16]
### Added
- Added support for usb sdr device index

## [0.3.15b]
### Bug fixing
- Typo...I swear

## [0.3.14b]
### Bug fixing
- Removed null device ID from new channel definition

## [0.3.13b]
### Added
- Added Definition for Temp from Thermopro TP12

## [0.3.12b]
### Changed
- Updated Autodiscovery to handle model values that were not in manufacturer-model format. 

## [0.3.11b]
### Added
- Added last_seen enity which should be the last time Home Assistant saw an update from 
  rtl_433.
- Added Freq definition to autodiscovery which reports device frequency
- Added channel definition to autodiscovery which report device channel 
- Added wind_max_km_h definition to autodiscovery

## [0.3.10b]
### Added
- Added consumption definition for gas meters
- Update rtl_433 to version 21.12-63-g2d041b5d

## [0.3.9b]
### Added
- Added port option in the config so now you can use other ports than the default 1883

## [0.3.8b]
### Added
- Added new definition for light_klx value from Brersser 7in1

## [0.3.7b]
### Added
- Added new whitelist option. Thanks to [@pdhruska](https://github.com/pdhruska) for the code.

## [0.3.6b]
### Added
- Added a definition for pressure in inHG 

## [0.3.5b]
### Changed
- More Rain gauge bug fixes. 

## [0.3.4b]
### Changed
- Updated Rain Gauge unit of measurements in device definition.

## [0.3.3b]
### Added
- Units to the config so you can set to metric or customary/imperial  

## [0.3.2b]
### Added
- Brightness defintion to attempt fix for #10. 
- KPa definition to auto discovery. 

## [0.3.1b]
### Changed
- Updated USB Condif to correct usb error. 
- Modified startup config
- Thanks @staniel1881 for the assist!

## [0.3.1]
### Changed
- Added Debug option to print messages to log
- Reverted back to old method of naming devices

## [0.3.0]
### Added
- this change log
### Changed
- Removed the weather device classes from mappings
- Switched Moisture mapping to humidity device class
- Added support for Subtypes in an attempt to fix the issue with not reading all the 5n1 sensors. 


## [0.2.0]
### Changed
- Updated repro url to fix Add-on store links
