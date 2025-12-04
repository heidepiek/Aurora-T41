Aurora LED Matrix – Teensy 4.1 Fork

This is a Teensy 4.1 fork of the beautiful Aurora LED Matrix project.

I first discovered Aurora through Manny Miller (Cinelights) on YouTube, and I immediately wanted to run it on my own 64x64 LED matrix. With his help, I got it working on a Teensy 3.6 with the SmartMatrix Shield v4. Recently, I brought the project back to life on a Teensy 4.1 with the SmartLEDShield for Teensy v5, and after some adjustments, it’s fully functional!



Features ✨

All original Aurora patterns work.

Audio-reactive patterns using the MSGEQ7 display correctly.

Animated GIFs are fully supported.

TXT message files scroll smoothly.

Clock works with the RTC module.



Known Limitations ⚠️

JSON file support is not working yet.

Menu required adjustments due to differences between Teensy 3.6 and 4.1 chips.



Quick Start / Installation 🚀

Install Arduino 1.8.12.

Install Teensyduino 1.53.

Connect your Teensy 4.1 with the SmartLEDShield for Teensy v5.

Open the Aurora-T41.ino file in Arduino IDE.

All required libraries are included in this repository.

Compile and upload to your Teensy.



💡 Tip: Make sure the board selected in Arduino IDE is Teensy 4.1 before compiling.



Libraries Used 📚

All libraries needed for this project are included in the repository. No additional downloads are required.

Screenshots / GIFs (optional)


Example of Aurora patterns running on a 64x64 matrix.



Credits 🙏

Original Aurora LED Matrix by Pixelmatix.

Special thanks to Manny Miller (Cinelights) for guidance and library support.



License 📄

This fork follows the same license terms as the original project.