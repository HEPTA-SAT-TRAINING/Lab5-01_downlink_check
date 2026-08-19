# Lab5-01: Downlink Check

Firmware that downlinks a 1-second count over XBee COM.

## Web Serial Monitor

Open in **Chrome or Edge**, then **Add Port** → **Connect** (38400 baud):

**https://hepta-sat-training.github.io/HEPTA-SAT-Serial_Monitor/**

You should see lines such as `count from COM = ...` every second.

## Firmware

Open `Lab5-01_Downlink_Check.ino` in the Arduino IDE and upload to your board. For library and submodule setup, see [src/README.md](src/README.md).
