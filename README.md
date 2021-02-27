![JB Game Lab](https://github.com/JayBee-git/GUN4IR/blob/master/img/JBGL-Logo_256p.png?raw=true)

# GUN4IR

This is a highly efficient and versatile DIY lightgun system, with a strong community and active development.
The main goal of this system is to provide a lightgun experience as close as possible from the arcade, while providing as much features and simplicity of use as possible.

Before starting, a small obligatory disclaimer: like with any DIY project, I am not responsible for any damage you might do to your hardware/yourself. Be sure to read everything carefully before using my firmware. I am not a professional in electronics. I am giving all the schematics and pics as examples, use them at your own risks.
And of course, this firmware cannot be sold alone nor in a package/hardware, it is completely free. If some people sold it to you, you were scammed.

# Features List
- Perfect line of sight accuracy: thanks to the 4 leds system, a ton of advanced math and pseudo 3D space calculation that does auto calibration and tracking in real time, you get a perfect line of sight accuracy all the time.
- One time calibration: calibrate the camera sensor and leds once, and then forget it, the aiming will still work perfectly no matter the angle, position, or if you disconnect your gun.
- Ultra low latency: this system uses a fast IR camera, and the firmware is heavily optimized, reducing the total processing latency to an average of 4ms (2ms ~ 7ms). Lowest latency of all modern lightgun systems.
No special software needed: everything is handled by the arduino, making it plug and play with any system that supports a mouse/keyboard or a controller input. No extra software needed (the GUI is optional).
- No external processing: no processing needed on the host platform, no cpu overhead, no overlay added to the game screen. You can use your games as usual.
USB and Bluetooth Mouse and Controller compatible: since it's using standard HID mouse, gamepad and bluetooth, it's compatible with everything that supports a usb/bt mouse & gamepad.
- Reduced minimum distance: thanks to the powerful tracking, this system allows you to play closer to the screen than most other modern systems, and even more if you add a wide lens or fisheye lens to the camera (any smartphone lens should work, even the cheap ones).
- Support every kind of screen: you can use this system pretty much on any screen type/ratio/size, it will just work.
- Full offscreen tracking/reload: it keeps track of your aiming even outside of the screen, and supports various offscreen options like offscreen reload.
- Full feedback support: you can add a solenoid, rumble motor and RGB led to your gun, and fully configure and control how each of them behaves and reacts to your games. It supports various functions like full auto and synchronisation with ingame feedback (for supported games).
- Auto reload support: you can activate it at any time to automatically reload your gun after 6 shoots.
- Nunchuck support: you can plug a nunchuck controller if you need more buttons.
- Setting saved inside the gun: each guns has its own memory, to save independent settings and customize each one to your liking.
- Quick mode switching with mode button: you can add a “Mode” button to your gun to triggers calibration when holding, or to quickly switch various modes:
   + Content mode (fullscreen/4:3).
   + Offscreen mode.
   + Input mode.
   + Pedal mode.
   + Auto reload mode.
- Full serial command support: you can use serial commands to set every gun mode, and sync the game feedback with the gun feedback.
- Fully featured GUI for supporters: for the supporters of this project, there is a full GUI with a lot of options and tools to configure every aspect of the gun.

# How to
Everything you need to start this project is in the pdf user guide in this repository.

# Firmware and GUI download
The files can be found in the repository or the release folder here:
https://github.com/JayBee-git/JB4PLG/tree/master/Releases

# GUI license
The firmware is free for anyone to use, but the GUI license is for donators only.
More info here:
http://forum.arcadecontrols.com/index.php/topic,161189.msg1697808.html#msg1697808

# Changelog
You can find the changelog either in the discord server of on the arcadecontrol forum (see the previous link)

# Contact
You can contact me easily in the official discord server here:
https://discord.gg/HJyfYja

