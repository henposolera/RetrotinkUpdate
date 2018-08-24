Updated version from https://github.com/Vykyan/retroTINK-setup that works with my TV

# HowTo:

Console/SSH into your fresh retropie install.

(NOTE: ssh can be enabled by either placing a blank ssh file in /boot/ or by configuring it from HDMI emulationstation before running this script).

Type/paste command (All one line)

`sudo apt-get install wget git -y && cd /home/pi/ && git clone https://github.com/henposolera/RetrotinkUpdate.git && cd RetrotinkUpdate && chmod +x ./retroTINK-setup.sh && sudo ./retroTINK-setup.sh`

Follow Instructions. (Make sure to change emulationstation theme to "tft-retrotink" once back in Emulationstation after reboot!

# Currently supported Libretro Systems:
 (Not emulator dependant, must be libretro/retroarch core)
 (Ex: snes will catch any SNES libretro core, ie, lr-snes9x,lr-pocketsnes etc)

atari2600,atari5200,atari7800,atarilynx,fba,fds,gamegear,gb,gba,gbc,genesis/megadrive,mame-libretro,mastersystem,msx,n64,neogeo,nes,ngp,ngpc,pc,pcengine,pcenginecd,psx,sega32x,segacd,snes,supergrafx,virtualboy,wonderswan,wonderswancolor

# Currently supported OTHER emulators/ports:

advmame (relies of advmame inbuilt support for changing resolutions),doom,quake
