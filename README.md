# OpenEVSE-Clone

This is an hardware design which is based on OpenEVSE, compatible with the OpenEVSE firmware, and suited to my needs.
Key changes in respect to the original OpenEVSE boards (version 5.5):
- Removed DC relais control (I use a AC controlled relais)
- GFCI detection removed (I use an external ELCB)
- Removed AC/DC converter (I use an external DIN rail mounted 12VDC supply)
- form factor adjusted to be fitted in a standard DIN rail housing
- Added H-Bridge driver for "cable lock" mechanism
- Added mounting for ESP32 Gateway
