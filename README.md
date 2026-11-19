# PixelSpoof

## Description
An LSPosed module that lets you spoof all device-specific properties of your device, selectively for individual apps, to a high end Pixel device. 
Currently Pixel 11 Pro XL (kodiak).

## Installation
1. Install the APK.
2. Enable the **PixelSpoof** module in **LSPosed Manager**.
3. Select the apps you need in module's scope.
4. Restart the selected apps.

## Features
* Build.prop values from latest Pixel 11 Pro XL official firmware.
* Features xmls from Pixel 11 series.

## Compatibility build
Android version fields, including SDK level, are read from the real device. The module still uses the Pixel 11 Pro XL identity profile and the LSPosed per-app scope.

The Actions test APK uses a separate package, `org.klab.pixelspoof.compat`, and a test certificate generated for that build. Disable the original module before enabling the test module, then select only the apps being tested and restart their processes.
