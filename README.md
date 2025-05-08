# mcu-server-watchdog
A pair of a simple heartbeat written in rust (running on PC/server) coupled with a watchdog (on a microcontroller) that connects the RST pins on the PCs mainboard should the heartbeat stop.

# My Board Config:
- uPesy ESP32 Wroom DevKit / ESP32 Dev Module
- CPU: 240 MHz
- Flash: 40 MHz
- Partition Scheme: 4MB with spiffs
- Upload Speed: 115200
- SPI Flash: 4 MB
