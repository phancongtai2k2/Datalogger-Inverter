# Datalogger Inverter - OTA firmware

Firmware images for the SRNE inverter datalogger (ESP32-S3), downloaded automatically by
deployed devices every night at 00:00.

- `versionfw.txt` - latest released version (`MAJOR.MINOR.PATCH`)
- `firmware/srne-datalogger-<version>.bin` - application image for that version

Published with `scripts/publish_ota.py` from the firmware project. Do not edit or overwrite
existing `.bin` files; release a new version instead.
