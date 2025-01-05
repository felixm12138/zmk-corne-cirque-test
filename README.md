# Corne with Cirque test repo

This is a test repo for a Corne keyboard that has Cirque Glidepoint connected via I2C to the standard Pro Micro pins (i.e. SDA/SCL at D2/D3) and DR pin connected to D1 (like nice!view adapter assumes).

I don't have the hardware to test and there are no guarantees that anything here works, but at least it should compile.

Use either `corne_cirque_left_with_device` and `corne_cirque_right`, or `corne_cirque_left` and `corne_cirque_right_with_device`. Cirques on both sides isn't supported.
