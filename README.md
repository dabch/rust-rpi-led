# rust-rpi-led
Updated Rust bindings for hzeller's rpi-rgb-led-matrix library. Included helper functions for displaying images loaded via [image-rs](https://github.com/image-rs/image) image processing library. Apart from these, the interface is largely identical to the C-interface of hzeller's library.

This library provides safe wrappers in the shape of `LedMatrix`, `LedCanvas` and `LedOptions` structs around the unsafe bindings generated by `rust-bindgen`. Except for `led_matrix_print_flags`, equivalents to all C methods are offered.

Heavily inspired by [Helvethor's Rust bindings](https://github.com/Helvethor/rust-rpi-rgb-led-matrix), which unfortunately were very out of date. This is why I created new ones, yay 🎉.

## Docs
rustdoc is following soon.
