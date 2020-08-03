# PKMN-Diamond-Bootleg-Reverse-Engineering

Project for reverse engineering a Pokemon Diamond bootleg with a reflashable Intel RD48F4400L0ZDQ0 chip


## Parts

This is a list of parts the repro cart uses


ROM: [RD48F4400L0ZDQ0](https://github.com/HDR/Datasheets/blob/master/RD48F4400L0ZDQ0.pdf)

Flash: [25PE40VP](https://github.com/HDR/Datasheets/blob/master/M25PE40.pdf)

Some sort of bank controller? (covered in epoxy)


## Pinout

Pins are numbered according to the image

![pads](BackNumbered.png)

**Todo:** Add BUS & RAM pinouts

| Pad | ROM | BUS | RAM |
|-|-|-|-|
| 1 | NC | CLK | Pin 7 |
| 2 | NC | D7 | Pin 8 |
| 3 | NC | D6 | Pin 2 |
| 4 | F1-OE/F2-OE | NC |  |
| 5 | D8 |  |  |
| 6 | D5 |  |  |
| 7 | D1 |  |  |
| 8 | D0 |  |  |
| 9 | D9 |  |  |
| 10 | D4 |  |  |
| 11 | D6 |  |  |
| 12 | D3 |  |  |
| 13 | D10 |  |  |
| 14 | D7 |  |  |
| 15 | A18 |  |  |
| 16 | D2 |  |  |
| 17 | D11 |  |  |
| 18 | F1-CE |  |  |
| 19 | A14 |  |  |
| 20 | A16 |  |  |
| 21 | A19 |  |  |
| 22 | A8 |  |  |
| 23 | A17 |  |  |
| 24 | F2-CE |  |  |
| 25 | A6 |  |  |
| 26 | D12 |  |  |
| 27 | A15 |  |  |
| 28 | A23 |  |  |
| 29 | D13 |  |  |
| 30 | A13 |  |  |
| 31 | A20 |  |  |
| 32 | A7 |  |  |
| 33 | A2 |  |  |
| 34 | D14 |  |  |
| 35 | A12 |  |  |
| 36 | D15 |  |  |
| 37 | F-WE |  |  |
| 38 | A10 |  |  |
| 39 | A21 |  |  |
| 40 | B5/B6(F1/F2-VCC) |  |  |
| 41 | A11 |  |  |
| 42 | A22 |  |  |
| 43 | A5 |  |  |
| 44 | A0 |  |  |
| 45 | GND | GND | Pin 4 |
| 46 | CLK/A24/F-VPP/F-WP/F-RST | 3.3V/Pin 3 |  |
| 47 | A9 |  |  |
| 48 | A4 |  |  |
| 49 | A5 |  |  |
| 50 | A1 |  |  |
| 51 | GND | GND | Pin 4 |