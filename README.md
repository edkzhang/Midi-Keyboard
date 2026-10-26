# Midi-Keyboard
I designed my own Midi keyboard with features like sliders, buttons, neo pixels, and more all while learning PCB design.
<img width="335" height="385" alt="3d midi 10" src="https://github.com/user-attachments/assets/e8fbf3cc-6ce9-45df-af4b-da2a800d549e" />
<img width="197" height="244" alt="MIDI9" src="https://github.com/user-attachments/assets/90f5683c-cb75-4219-b0e7-99187b85910d" />
Apps: KiCad (with extra plugins)

  For my 3rd week of hack club, I designed a Midi using KiCad. I read the guide and for a long time, it was smooth sailing. I finished the schematics pretty quickly and finished the footprints quickly, but it started getting hard when I had to use the PCB editors.

  The format for the PCB editor was completely new. It took a while to adjust and to fix the mistakes I made in the footprint editor. I was originally going to make a piano shape like the guide, but that was too hard, so I resorted to rounded off rectangles.

  Later, the footprint shape was way too small so I had to dedicate a majority of my time to figuring out why the new footprint shape wouldn't update into the PCB editor. Instead of finding the problem, I just made a new one and stuck with it.

  Wiring was probably the most confusing. There were so many lines, and it was very hard to follow the guide from there on. All I did was follow the blue lines from the rat nest and miraculously, it somehow worked out. I then downloaded the plugin to export the model and went on to calculate prices.

  It was a long journey, but definitely worth it. It was my first time ever dealing with PCB design and this was scary but all the more fun. I look forward to working with PCB further into the future.

  Below, I've attached a link to my model:

  [Erics_MIDI_bom.csv](https://github.com/user-attachments/files/33944820/Erics_MIDI_bom.csv)Designator,Footprint,Quantity,Value,LCSC Part #
"D1, D2, D3",LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount,3,SK6812MINI-E,
J1,Capacitive Keys Shape v2,1,Conn_01x07,
"RV1, RV2",Potentiometer_Bourns_PTA1543_Single_Slide,2,Slider,
"SW1, SW2, SW3",Kailh Choc Low-Profile Switches,3,SW_Push,
SW4,RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm,1,RotaryEncoder_Switch_MP,
U1,Waveshare ESP32-S3-Zero,1,Waveshare ESP32-S3-ZERO,

Thanks :)
