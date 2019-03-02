# My Ender 3 firmware config

This is a firmware package, modified to suit my needs and hardware in my Ender 3 printer.

*Based on the [TH3D Unified Firmware Package](https://th3dstudio.freshdesk.com/support/solutions/articles/43000460446-th3d-unified-firmware-package)*

### Features
- Enabled `SLOWER_HOMING` - no more smashing into the endstops and frame
- Fixed Y axis offset
- Reduced 5015 fan vibrations
- Enable `DISABLE_BOOT` to achieve shorter bootup time and free up memory
- Configured for acrylic glass build plate printing (AKA PMMA, FilaPlate).
    - `BED_MAXTEMP` set to 25&deg;C
    - `PREHEAT_1_TEMP_BED` set to 20&deg;C
    - `PREHEAT_2_TEMP_BED` set to 20&deg;C

