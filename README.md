Burnin'Rubber for MEGA65
========================

Get ready to hit the pixelated streets in Burnin' Rubber, the MEGA65 edition! Originally released by Data East in 1982 as Bump 'n' Jump, this classic arcade racer puts you in command of a high-speed, action-packed car. Leap over obstacles, strategically bump opponents off the road, and navigate challenging courses filled with twists and turns.

Now optimized for the MEGA65 computer, Burnin' Rubber retains all the retro charm of the original. Immerse yourself in the nostalgic graphics and addictive gameplay that made Bump 'n' Jump an arcade sensation. Take on the challenge, master the tracks, and relive the golden era of arcade gaming with Burnin' Rubber on MEGA65!

This core is based on the
[MiSTer](https://github.com/sho3string/Arcade-BurningRubber_MiSTer)
Burnin'Rubber core which
itself is based on the work of [many others](AUTHORS).

[Muse aka sho3string](https://github.com/sho3string)
Ported the core to the MEGA65 in 2023.

The core uses the [MiSTer2MEGA65](https://github.com/sy2002/MiSTer2MEGA65)
framework and [QNICE-FPGA](https://github.com/sy2002/QNICE-FPGA) for
FAT32 support (loading ROMs, mounting disks) and for the
on-screen-menu.

How to install the Burnin'Rubber core on your MEGA65
----------------------------------------------------

1. **Download ROM**: Download the Burnin'Rubber ROM ZIP file from the web.

2. **Copy the ROMs to your MEGA65 SD card**: Copy the contents of the folder with
   the ROMs to your MEGA65 SD card. You can use either the bottom SD card tray
   of the MEGA65 or the tray at the backside of the computer (the latter has
   precedence over the first).
   The ROMs need to be in the folder `arcade/brubber`.
   
   Copy the brcfg provided to 'arcade/brubber` on the sdcard.

   This core does not support the Bump 'n' Jump clone. I may add support for this in the future if there is demand.

3. **Setting up dip switches**

   See below for a description of DIP switches in the game.
   
   [Link](https://www.arcade-museum.com/dipswitch-settings/7241.html)


9. **Download and run the Burnin'Rubber core**: Follow the instructions on
  [this site](https://sy2002.github.io/m65cores/) to download and run the a core on your MEGA65.

10. **Common problems [WIP]**
