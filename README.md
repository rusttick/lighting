
# hello_world


https://docs.espressif.com/projects/esp-idf/en/latest/esp32s3/get-started/index.html

This is esp32s3 chip with 2 CPU core(s), WiFi/BLE, silicon revision v0.2, 2MB external flash


```bash
source ~/src/esp-idf/export.sh

cd hello_world

format.sh main/hello_world.c

idf.py build
idf.py flash monitor

^]
```
