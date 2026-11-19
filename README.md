# Sofle Choc (ZMK)

ZMK configuration for a classic reversible Sofle Choc with two `nice_nano_v2` (SuperMini nRF52840) controllers, rotary encoders, no OLEDs, and no RGB.

- **Left half (`sofle_left`)**: Split central, connected directly to the host over USB (`&out OUT_USB` bound on Layer 1).
- **Right half (`sofle_right`)**: Split peripheral over 2M PHY BLE (`7.5 ms` connection interval).
- **Soft-off combo**: Hold `Q + S + Z` for 2 seconds to enter deep sleep; wake with the reset button.
- **Studio**: Manage keymaps and runtime settings via [Dya Studio](https://studio.dya.cormoran.works/).

## Sofle Keymap

![Sofle Keymap](keymap-drawer/sofle.svg)
