# Rust Pico2 sandbox

## What's in here

* Example of how to blink an LED

## Rough plan

* Be able to control LED state via USB
    * Use embassy's USB stack
    * This probably requires a custom USB class
    * Example of USB HID device
      [here](https://github.com/embassy-rs/embassy/blob/main/examples/rp235x/src/bin/usb_hid_keyboard.rs)
