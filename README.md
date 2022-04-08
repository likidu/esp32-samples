# esp32-samples
ESP32 samples to test with the Azure RTOS porting

## Use usbipd to flash from WSL2

You need to add the udev rules for Linux for the board:

https://github.com/pyocd/pyOCD/tree/main/udev

1. Copy content from https://github.com/pyocd/pyOCD/blob/main/udev/50-cmsis-dap.rules

