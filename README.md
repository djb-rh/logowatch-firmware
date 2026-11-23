# LogoWatch firmware updates

Signed firmware for LogoWatch watches (M5Stack StopWatch). The watches fetch these files
themselves; there is nothing to install by hand here.

`latest.txt` names the newest version and is signed; a watch refuses anything that isn't.

The firmware includes these open-source parts:

| part | licence |
|---|---|
| [Arduino core for ESP32](https://github.com/espressif/arduino-esp32) 3.3.12 | LGPL-2.1 |
| [ESP-IDF](https://github.com/espressif/esp-idf) 5.5 | Apache-2.0 |
| [ESPAsyncWebServer](https://github.com/ESP32Async/ESPAsyncWebServer) and [AsyncTCP](https://github.com/ESP32Async/AsyncTCP) | LGPL-3.0 |
| [M5Unified](https://github.com/m5stack/M5Unified) and [M5GFX](https://github.com/m5stack/M5GFX) | MIT (M5GFX also FreeBSD) |
| [ArduinoJson](https://github.com/bblanchon/ArduinoJson) | MIT |
