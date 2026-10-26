# Dexter keypad
<img width="622" height="398" alt="image" src="https://github.com/user-attachments/assets/f43a280f-f489-4f97-a5ca-b62bb068769a" />

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
|MX Switches               |1  |Temu      |$2.84      |$2.84       |https://www.temu.com/ec/switches-de-teclado-mecanico-intercambiables-para-reemplazo--con-switches-cherry-en---marron-y-negro-g-601099814401749.html?_oak_mp_inf=ENXtpaen1ogBGh1nb29kc19ianN5OXBfc29sZF9vdXRfc2ltaWxhciCkg%2FKwlzQ%3D&top_gallery_url=https%3A%2F%2Fimg.kwcdn.com%2Fproduct%2Ffancy%2F06049d86-3cc3-4781-9007-f4511eb9edf9.jpg&spec_gallery_id=601099814401749&refer_page_sn=10032&freesia_scene=25&_oak_freesia_scene=25&_oak_rec_ext_1=Mjk3&_oak_gallery_order=927050043%2C424683148%2C1200427065%2C1332313479%2C2104336086&refer_page_el_sn=200970&ab_scene=1&refer_page_name=goods&refer_page_id=10032_1792982941107_oiltpbxe8e&_x_sessn_id=jwrfwb0n6x&no_cache_id=gxlv5&is_back=1                                                                            |      |
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





