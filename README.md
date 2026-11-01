# ZMK Config

This repository contains the configuration files for a ZMK-powered keyboard.

I usually compile the keyboard firware locally, that's way faster.

rake clean

rake build

rake flash

For German layout put #include <dt-bindings/zmk/keys.h> into the keymap code in behaviors
For placing mouse movement on keys/rotary encoders put #include <dt-bindings/zmk/pointing.h> in behaviors
in both of those files the names for the individual keys are defined.
