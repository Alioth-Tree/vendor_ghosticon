### GhostIcon

Lawnicon mod 
Most icons import for TeamFiles PLE icon overlay
So, Thanks to ThemFiles for icons

clone 
```bash
   git clone https://github.com/Alioth-Tree/vendor_ghosticon.git vendor/ghosticon
```

To build with GhostIcon add this line in device.mk or (rom)_(device).mk
```bash
   # GhostIcon
   $(call inherit-product-if-exists, vendor/ghosticon/ghosticon.mk)
```
Need to pick this commit in ThemePicker of rom
```bash
   https://github.com/Spark-Rom/packages_apps_ThemePicker/commit/f0f9d17
```
