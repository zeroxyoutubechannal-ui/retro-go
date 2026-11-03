# ESP32-S3-N16R8 (custom: ILI9341 + SD SPI + joystick + 5-way)
Module: ESP32-S3-N16R8 (16MB flash, 8MB octal PSRAM). GPIO26-37 are NOT usable (flash/PSRAM).
Also avoided: 0, 3, 45, 46 (strapping), 19, 20 (USB), 43, 44 (UART), 38, 48 (RGB LED on some revisions).

| Function | GPIO |
|---|---|
| LCD SCK / MOSI / CS / DC / RST / LED | 12 / 11 / 10 / 9 / 8 / 14 |
| SD SCK / MOSI / MISO / CS | 17 / 16 / 15 / 18 |
| Joystick VRx / VRy / SW | 4 / 5 / 6 |
| 5-way U / D / L / R / Center | 1 / 2 / 42 / 41 / 40 |
| I2S (optional) BCK / WS / DATA | 47 / 21 / 39 |
