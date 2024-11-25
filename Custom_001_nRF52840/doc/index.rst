.. zephyr:project:: beacon-sensor
   :name: Beacon_Sensor
   :relevant-api: gpio_interface i2c_interface qspi_interface

   Measure and collect environment data and broadcast over BLE.

Overview
********

The device is designed based on Nordic-nRF52840 MCU.

The device has been equiped with below components:

#. nRF52840: Multiprotocol Bluetooth 5.4 SoC supporting Bluetooth Low Energy, Bluetooth mesh, NFC, Thread and Zigbee
#. LIS3DH: ultra-low-power high-performance 3-axis "nano" accelerometer
#. SHT40: 4th Gen. High-Accuracy, Ultra-Low-Power, 16-bit, Relative Humidity and Temperature Sensor
#. DRV5032FADBZR ultra-low-power digital-switch Hall effect sensor
#. W25Q64JV: 64M-BIT SERIAL FLASH MEMORY WITH DUAL, QUAD SPI
#. LED: as indicator
