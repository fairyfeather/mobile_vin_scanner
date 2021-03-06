# Mobile VIN Scanner SDK

This is repo for Mobile VIN Scanner SDK created and maintained by bees4honey.

Mobile VIN Scanner SDK allows developers to quickly embed VIN scanning functionality into their iOS, Android and PhoneGap powered apps.

**Why we created the SDK?** Well, we were in need of good and fast VIN scanner for both iOS and Android. We didn't find any good solution on market, though there are some open source libs, like ZXing or ZBar, they do not provide any acceptable level of quality and performance in case of VIN scanning. 

So we created our own VIN Scanner technology keeping in mind that it should be:
a) very fast;
b) very reliable.

Our SDK is intended to scan only VIN barcode and nothing more, so we have optimized scanning for this one task. We do not use all amount of data received from camera, that's why our SDK is fast. Also as far as we know that we are going to scan VIN, we have implemented verification algorithms, which ensure that VIN number received is correct.

## Try our technology

There are two ways to try our VIN scanning technology.

### Try our free apps:
1. iOS https://itunes.apple.com/us/app/vin-barcode-scanner/id497948900?mt=8
2. Android https://play.google.com/store/apps/details?id=com.bees4honey.vinscanner

### Download appropriate project to try it in your app:
1. ios_scanner_sdk - native iOS project, which you can build and try. 
2. android_scanner_sdk - native Android project.
3. phonegap_vin_scanner_plugin - PhoneGap plugin for iOS and Android platforms.

## Licensing

You are free to download any of our projects and use it in development purpose inside your app. 

You are not allowed to comercialize (that is, sell, rent, trade or lease) Mobile VIN Scanner SDK, 
modify, recompile, reverse engineer or otherwise alter the Mobile VIN Scanner SDK. Please read more about licensing
in license_agreement.txt

Without License Key SDK will work in demo mode and amount of scans will be limited per install. 

**Please contact us at vin@bees4honey.com for purchasing details.**

Thanks!

## Phonegap plugin installation

We also support Phonegap VIN Scanner plugin for iOS and Android platforms.

**WARNING:** since VIN Scanner plugin heavily uses native code for both iOS and Android platforms, the Adobe Phonegap Build cloud service is not supported. To use our plugin you need to build project using Phonegap command line tools.

Only Android versions 4.0 and higher and iOS versions 7.0 and higher are supported in Phonegap plugin.

Installation instructions:

1. Generate your project using "phonegap create" command.
2. Add a plugin to your project using the following command:

```
phonegap plugin add https://github.com/bees4honey/mobile_vin_scanner#:/phonegap_vin_scanner_plugin
```


You can find usage example in plugins/com.bees4honey.vinscanner/index.html file in Phonegap project's folder.