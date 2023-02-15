# Treble Overlay for Xiaomi Redmi K50

This Magisk module places the Treble Overlay on `/system/product/overlay` and places `android.hardware.lights-service.mediatek` (a patched file from xda) to `/system/vendor/bin/hw`, since `/system` is read-only on Magisk systems.

Overlays can be found in [phhusson's repository](https://github.com/phhusson/vendor_hardware_overlay).


## Using this Module

1. Download the zip file
2. Move it to your device (through `adb push` for example)
3. Install the module using Magisk

