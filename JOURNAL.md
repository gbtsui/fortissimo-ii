---
title: "Fortissimo-II"
author: "gbtsui"
description: "A split ortholinear coding/multilanguage keyboard for efficient typing and language switching!"
created_at: "2025-06-04"
---


## 4 June 2025
So this is the start of my keyboard! Hi! I'm Gabriel. This is going to be probably my first medium-scale PCB project!
I'm going to actually start design work for this on Sunday because I'm going to compete with my friends to see who can
keyboard the fastest. But my basic design concept is:

- split ortholinear design
- physical switch to toggle between languages/scripts (US QWERTY, French Canadian Multilingual, Greek layout, custom Hiragana layout, custom Katakana layout)
- low profile design
- neopixels reacting to events and languages
- OLED displays per side
- USB hub
- RP2040 (either a stamp or just a breakout board)

Yeah, that's about it!

## 13 June 2025
So I actually forgot to journal the work I did. On Sunday (8 June), I got most of the schematic done and started working on the PCB itself.
![image](https://github.com/user-attachments/assets/1787e89b-7731-4796-b425-64ecb2852213)
Unfortunately, I was really really dissatisfied with the PCB because it was sad and bad and low quality. So today I deleted the work I had so far and started fresh.

A problem that I noticed was that my hub had to be able to handle 5V1A through VBUS. I could use thicker copper traces (2oz?) but that would be kinda expensive. Then again, I'm using the same amount of copper regardless so that it can all handle the current. So I honestly have no idea what to do now; I'm just going to wire it up anyways and hope for the best. Also, the components that I'm using need to be able to handle all of that.

I have 35 SK6812Minis, a PGA2040, an SSD1306, and 3 downstream USB ports. I might be fried, honestly. I need to be running, like, what, 2.1A? to get everything running? I might lower the neopixel brightness so my board doesn't implode on itself.

Gonna start wiring now. Wish me luck.
