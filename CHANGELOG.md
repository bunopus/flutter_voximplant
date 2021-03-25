# Changelog

## 2.6.1
* Fix for [#20](https://github.com/voximplant/flutter_voximplant/issues/20)

## 2.6.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.21.3
  and Voximplant iOS SDK 2.36.2
* VIAudioFile._type private field changed to VIAudioFile.type public final field

## 2.5.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.21.0
  and Voximplant iOS SDK 2.35.0
* Fix [VICall.onCallAudioStarted](/docs/references/fluttersdk/call/vicall#oncallaudiostarted)
  callback execution on iOS

## 2.4.3
* Fix a bug leading to non-execution of VIAudioFile.stop() Future in some cases

## 2.4.2
* Fix a crash on stop non-looped VIAudioFile (iOS)

## 2.4.1
* Reformat code according to Dartfmt
* Fix VIAudioDeviceManager.getAudioDevice always throws issue

## 2.4.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.20.4
  and Voximplant iOS SDK 2.34.3
* Introduce VIAudioFile API

## 2.3.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.19.0 
  and Voximplant iOS SDK 2.33.0
* Introduce Messaging API
* Fix for [#14](https://github.com/voximplant/flutter_voximplant/issues/14)

## 2.2.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.17.0 
  and Voximplant iOS SDK 2.31.0
* Supporting the new Android plugins APIs based on FlutterPlugin
* VIClient.conference method added
* VIEndpoint.place value added
* VIEndpoint.onEndpointRemoved callback added

## 2.1.2
* Update iOS platform code to use Voximplant iOS SDK 2.30.0
* Xcode 11.4 support added
* VIVideoRenderer null handling improvements
* VIClient bundleId won't be set to native SDK if it is null

## 2.1.1
* VIVideoFlags incorrect initialisation fix

## 2.1.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.16.1
  and Voximplant iOS SDK 2.29.0
* Improve video rendering on iOS
* VICameraManager.selectCamera is now available for iOS
* Add VICall.getCallDuration API

## 2.0.0
* Update iOS platform code to use Voximplant iOS SDK 2.26.0
* Add 'VI' prefix to public API to avoid conflicts with other packages
* Add video call functionality
* Add camera management functionality
* Improve multiple call management
* Improve error descriptions for iOS
* Public API will no longer throw PlatformException. All exceptions are now wrapped 
  with VIException. Error codes for VIClient and VICall are described in VIClientError
  and VICallError classes.
* Fix build issues in example project
* Changed minimum Flutter SDK version to 1.10.0

## 1.2.0
* Update Android and iOS platform code to use Voximplant Android SDK 2.15.0
  and Voximplant iOS SDK 2.25.2
* Native code refactoring

## 1.1.0
* Add API for CallKit integration on iOS platform
* Update Android and iOS platform code to use Voximplant Android SDK 2.14.1
  and Voximplant iOS SDK 2.25.1

## 1.0.0
* Audio call functionality
