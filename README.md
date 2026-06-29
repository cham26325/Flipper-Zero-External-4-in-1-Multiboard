# Flipper Zero 4-in-1 Multiboard

The Flipper Zero 4-in-1 Multiboard combines ESP32-S3, NRF24, CC1101, GPS, a 0.91-inch OLED screen, antennas, and a protective case into one compact expansion board.

![Product Image](images/Kutoubee_4_in_1_Multiboard_for_Flipper_Zero.jpg)

## External CC1101 Signal Improvement

The board includes an external CC1101 sub-GHz radio module with an external antenna connector.

Compared with the built-in Flipper Zero sub-GHz radio, the external CC1101 module can provide stronger measured signal levels under the same basic test conditions.

## Signal Level Comparison

Check video of the whole testing here: https://www.youtube.com/shorts/tDweoz1FHr4

We conducted a same-condition 433.92 MHz comparison test using a TinySA Ultra spectrum analyzer.

The Flipper Zero built-in CC1101 radio produced a peak received signal level of approximately -47.8 dBm. After connecting our external CC1101 expansion module with its dedicated 433 MHz antenna, the measured peak received signal level increased to approximately -10.0 dBm.

Under this specific test setup, the external module produced an observed improvement of approximately 37.8 dB in received signal level.



| Test Item | Observed Signal Level |
|---|---:|
| Flipper Zero built-in sub-GHz radio | approx. -47.8 dBm |
| 4-in-1 Multiboard external CC1101 | approx. -10.0 dBm |
| Observed improvement | approx. +37.8 dB |



![Product Image](images/flipper_zero_CC1101_comparison.webp)
## Test Summary

In this comparison, the external CC1101 module on the 4-in-1 Multiboard produced an observed signal level improvement of approximately **37.8 dB**.

This suggests that using an external CC1101 module with a suitable external antenna can significantly improve measured sub-GHz signal performance compared with the built-in radio path.

## Integrated Modules

- ESP32-S3
- NRF24
- CC1101
- GPS
- 0.91-inch OLED screen
- External antennas
- Protective case with pin guard


For more product information, photos, and availability, visit:

https://kutoubee.com/product/flipper-zero-4-in-1-multiboard/
