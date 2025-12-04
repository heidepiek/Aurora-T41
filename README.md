Aurora LED Matrix – Teensy 4.1 Fork

In my opinion, Aurora is one of the most beautiful LED matrix projects out there. I first discovered it through Manny Miller from Cinelights, who made a fun little project on his YouTube channel. After seeing that, I really wanted to get Aurora running on my own 64x64 LED matrix.

With Manny’s help, I got the right libraries and managed a working version on my Teensy 3.6 with the SmartMatrix Shield v4. Time passed, and recently I decided to bring the project back to life — this time on a Teensy 4.1. As usual, it wasn’t entirely smooth sailing, but I finally have a working version!

What Works

All original patterns run perfectly.

Audio-reactive patterns using the MSGEQ7 function as expected.

Animated GIFs display correctly.

TXT message files scroll beautifully.

Clock works with the RTC module.

What Doesn’t

JSON file support isn’t working yet.

The menu required adjustments due to the differences between Teensy 3.6 and 4.1 chips.

Despite these minor issues, the project is fully playable and enjoyable. It’s a fun, working Aurora experience on a Teensy 4.1 — scroll messages, watch patterns, and enjoy the LEDs!
