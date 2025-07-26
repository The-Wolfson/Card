---
title: "Card"
author: "Joshua Wolfson"
description: "An NFC PCB business card with LED feedback."
created_at: "2025-07-23"
---

**Total time spent: 7h**

# 23rd July: Schematic and Footprint.

I'm following the [hacker-card tutorial by maggie-j-liu](https://jams.hackclub.com/jam/hacker-card), one challenge with it is that it is for easyEDA, while I'm using KiCad. The antenna is gonna be a struggle, but that's a problem for later. One variation I'm making is that I'll be using 3 LEDs instead of one. 
I also started the footprint, it's pretty basic with just my name. So I'll be sure to add some contact details as well.
Anyway, this was a hair brained scheme thought up in the middle of the night, so I'm for bed. More to follow.

![Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/10acbd83d160ae6438abed21062b2eee3231663e_screenshot_2025-07-23_at_10.36.57___pm.png)

**Time: 2h**

# 24th July: Antenna and Footprint iteration.

The antenna is by far the most challenging part of this project, the tutorial I'm following uses easyEDA, but I'm using KiCad. The NFC chip needs an inductance of 2.7-2.9, I'm using https://neurotech-hub.github.io/KiCad-Antenna-Generator/ to calculate and achieve an inductance of 2.77.
The pcb footprint also needed to be redone as room was needed for my email address and whatnot.
I finished off the session by drawing consecutive outlines on the back of the board for visual appeal.

![Design](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2e48c8de7f29d6485e1fabc75df7f8e259682e0a_screenshot_2025-07-26_at_10.56.15___am.png)
**Time: 4h**

# 25th July: JLCPCB Pricing and specs.

Right now I'm tossing up wether to utilise PCBA or not; on the one hand the parts are small and I'm not confident in my ability to solder, on the other it pretty much triples the price.
Along with this is that while a black PCB looks way more professional, it is about $10 more expensive.
However, if JLCPCB plays nice, and I use some coupons. I can minimise the price to $30.

**Time: 1h**
