# Dexter keypad
<img width="742" height="482" alt="image" src="https://github.com/user-attachments/assets/2f14537c-6d89-4aa5-a592-f39cd337a331" />

This is a custom keypad built based on Half Life's Week 3 starter project by [KaiPereira](https://github.com/KaiPereira), with some edits by me!

## Overview

This keypad uses Capacitive Keys, which are exposed copper pads that catch your electrostatic energy and send a signal to special pins in your microcontroller. The keypad has 7 keys and uses the Waveform ESP32-S3-Zero. 

It also includes 3 switches for custom functionality and a rotary encoder (potentiometer) with a built-in click functionality. Finally, it includes 3 SK6812MINI-E LEDs for RGB or regular lightning.

## Features

* MIDI output through USB-C (pending)
* MicroPython firmware (basic [template](https://github.com/KMKfw/kmk_firmware/blob/main/docs/en/Getting_Started.md))
* Programmable LEDs
* 3 switches for extra functionality
* 4 M3 3.2mm mounting holes
* Potentiometer with built-in switch for extra functionality

## Button layout
* Button 1: set mode to minor notes
* Button 2: set mode to flat (bemols) notes
* Button 3: set mode to sharp notes
* Potentiometer switch: reset to normal mode (major notes)

Button 1, 2 and 3 have their respective LEDs, which will turn on when they are clicked. Only one may turn on at the same time.

NOTE: this is planned to be added as firmware in the build weeks, so I can safely flash and test the firmware as no template firmware was provided

## BOM Table
|Item                                          |Qty|Supplier   |Cost/item|Total Cost|link                                                                                                                                          |Note                                                       |
|----------------------------------------------|---|-----------|---------|----------|----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
|Waveshare ESP32-S3-Zero                       |1  |Waveshare  |$5.49    |$5.49     |https://www.waveshare.com/esp32-s3-zero.htm?sku=25081                                                                                         |                                                           |
|SK6812MINI-E                                  |3  |Ebee       |$0.0808  |$0.404    |https://www.ebee.com/product-detail/opsco-optoelectronics-sk6812mini-e_620740.html                                                            |                                                           |
|Kailh Choc Low-Profile Switches               |3  |Ebee       |RFQ      |RFQ       |https://www.ebee.com/product-detail/kailh-cpg135001d03_873001.html                                                                            |Price pending because supplier takes too long to answer RFQ|
|RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm|1  |Temu       |$1.21    |$1.21     |https://www.temu.com/ec/1pc-accesorio-de-robot-s----rotatorio-ec11-potenciometro-digital-para-altavoz-con--5-pines-20mm-g-606209147009488.html|                                                           |
|PCB                                           |1  |Local store|$3.50    |$3.50     |https://novatronicec.com/index.php/product/fabricacion-de-circuitos-impresos-pcb/                                                             |Payment done in person so no shipping costs                |
|                                              |   |           |         |          |                                                                                                                                              |                                                           |
|Estimated total shipping                      |1  |           |         |$20.00    |                                                                                                                                              |                                                           |

## Screenshots
<img width="742" height="482" alt="image" src="https://github.com/user-attachments/assets/73b20a8c-0cea-4a51-92a0-292d3d3bd57a" />

Front render

<img width="742" height="482" alt="image" src="https://github.com/user-attachments/assets/bb28dabb-e363-4e5e-850a-b83f7a419105" />

Back render

<img width="682" height="376" alt="image" src="https://github.com/user-attachments/assets/8b2ea44c-a425-4c54-ba46-a3662b5e73c5" />

PCB Layout

<img width="349" height="373" alt="image" src="https://github.com/user-attachments/assets/b85df704-11d1-444a-9e5c-5c75bd283d82" />

Schematic





