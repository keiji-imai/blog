---
title: Watercooled Battery Coldplates
date: 2023-02-26
draft: False
showLikes: True
description: "Machining watercooled battery cold plates for MIT Motorsports"
series: ["MIT Motorsports"]
series_order: 2
---

I machined four coldplates for MIT Motorsports. Coldplates are aluminum parts that have channels for cold water to pass through. The coldplates I made were for the battery. We make them in multiple parts and have them brazed so that they are watertight. 

[Dip Brazing](https://www.dipbraze.com/what-is-dip-brazing/) is a process where you cover a joint with a molten filler metal and let it harden to form a watertight bond between them. The last time we tried making cold plates, they couldn't be brazed properly because we used 7075 Aluminum alloy, which forms microcracks when welded and has [too low of a melting point to be brazed effectively](https://www.mtm-inc.com/brazing-aluminum.html). This time we are using 6061 aluminum which is great for brazing.

First I faced the stock so that it would be flat on the bottom. I used a vacuum plate for this but decided against using it for the actual machining because it was getting shifted. 

{{<youtube g_x4HJx3ttU>}}

Then I applied tape to the faced side of the stock as well as a larger piece of stock (which was also faced) and superglued the tape together.

![Tape](images/coldplate_tape.jpg)

Next I clamped the larger stock to the Haas with toe clamps and used a dial indicator to make sure the stock was straight.

![Clamp](images/coldplate_clamped.jpg)

I probed the stock to find its center.
{{<youtube mqj094Nwo8o>}}

I found the bottom height of the stock by probing off of two layers of tape.

![Probe](https://media.giphy.com/media/MWXqxALGJWU6QbRhwD/giphy.gif)

Once everything was set up, I ran the file. The first time I ran the gcode, it got really big burrs. The endmill was dull, so it was pushing the metal up instead of cutting it. So I replaced the endmill and ran the program again. 

The entire operation was an hour and a half of runtime so I only recorded the coolest parts. In this video it drills the holes super quickly.
{{<youtube v4U_A5ukTl4>}}

We removed the plate from the larger stock using a chisel and hammer. The tape can be peeled off easily, leaving nothing behind on the part.
{{<youtube gXv47nosnJo>}}

We got a decent surface finish:
![Closeup](images/coldplate_closeup.jpg)

I made four coldplates in total.

![Stack](images/coldplate_stack.jpg)

The water will come in through connectors that are threaded into these cylindrical parts that will be brazed to the coldplate.
![Threads](images/coldplate_threads.jpg)

