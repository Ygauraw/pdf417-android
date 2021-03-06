# Release notes

## 2.0.1
- support for having camera activity in landscape mode - extended support to Android 2.1 devices
  (fixing Samsung Galaxy Mini issues)

## 2.0
- new simpler API
- better support for custom user interface
- ability to scan multiple barcodes without closing camera activity (from custom UI only)
- added torch control button to default PDF417.mobi demo app
- PDF417CustomUIDemo contains example of controlling camera torch and example of scanning multiple barcodes without closing camera activity
- documentation updates
- support for scanning damaged and non-standard PDF417 barcodes - if barcode checksum is not correct, returned result is marked as "uncertain"

## 1.6
- autofocus and flash features are now optional (play store app now supports much more devices)

## 1.3.1
- better and faster barcode detection
- faster detection and decoding performance
- additional bugfixes

## 1.3
- adding support for front facing cameras
- fixed memory leaks

## 1.2.1
- fixed race condition in detection display

## 1.2.0
- support for micro PDF417 standard

## 1.1.0
- support for reading raw barcode data
- support for reading damaged and non-standard PDF417 barcodes

## 1.0.1
- support for case insensitive package matching when checking for license key
- added release notes

## 1.0
- added API for enabling 1D barcode scanning
- scan popup can be now removed even when using free non-commercial license

## 0.9
- support for reading PDF417 with error correction 0 and 1
- better support for Sony Xperia S
- fixed 'invalid license key' bug when resumin application from background

## 0.8
- Initial release
- Scanning support for pdf417 and QR code