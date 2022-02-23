This is the firmware for the ffkb:
* https://fingerpunch.xyz/product/faux-fox-keyboard/
* https://discord.gg/ewS6xbCgPb
* https://github.com/sadekbaroudi/fingerpunch/tree/master/ffkb

Note that this is pre-configured for 3 rotary encoders, though the ffkb supports an OLED or pimoroni trackball in the center. You may need to adjust the firmware to support them. If you enable another feature, be sure to disable the encoder_3 since it shares pins with the other features.

For an example of firmware that supports an OLED, see:
* https://github.com/NCKiser/zmk-ffkb
