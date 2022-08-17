# ConnectedBatteryCharger
ESP32 Enabled Battery Charger - Ready to Interface with ORA System.

Credits to https://github.com/opensolarproject/OSPController for the interfacing with DPS5005!

# HW BOM
- ESP32 (e.g. Lolin 32 Lite)
- 5V Regulator (with wide Input Range)
- DPS5005 (later also Support for 5020)
- 0.91" Oled I2C Display
- 4 pin Connector for USB
- 2x XT60E
- Case: E.g.: https://www.amazon.de/gp/product/B09YTV3B8J/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1
- 3d printed Cover (see stl)

# HW Wiring
ESP32 -> 0.91" Oled
- 3.3V -> VCC
- GND -> GND
- GPIO 15 -> SDA
- GPIO 2 -> SCL

ESP32 -> DPS5005 / 5020

(see https://github.com/opensolarproject/OSPController/wiki/Step-2-Hardware-Build)

- GND -> Pin 1
- GPIO16 -> Pin2
- GPIO17 -> Pin3
