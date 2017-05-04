Sample code for driving MAX44009 ambient light sensor via ESP-IDF's I2C master driver
====================

See main code main.c_.

----------
About
----------

This sample code implement procedures to read values from MAX44009 ambient light sensor via ESP-IDF's I2C master driver, based on `Max Integrated's MAX44009 datasheet`_.

----------
For local setup
----------

For your local setup, connect SDI pin to GPIO 15 pin and the SCK to GPIO 2 pin as they are default ports (I2C_SDA, I2C_SCL) for I2C master according to `ESP32 datasheet`_, C.4. IO_MUX, Page 49.

.. _main.c: https://github.com/yanbe/max44009-esp-idf-i2c/blob/master/main/main.c
.. _ESP32 datasheet: https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf
.. _Max Integrated's MAX44009 datasheet: https://datasheets.maximintegrated.com/en/ds/MAX44009.pdf
