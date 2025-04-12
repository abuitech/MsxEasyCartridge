![MsxEasyCartridge](Images/EasyCartridge.jpg)
# MsxEasyCartridge (Work in progress)
Msx Easy Cartridge is an user friendly cartridge linker for MSX : it allows to run MSX cartridge rom up to 128Ko.
It is based on a Rasberry Pi pico with 14Mo built in flash memory and is made as easy to use with a built-in cartridges browser.
## Functionalities
* Run MSX cartridge - supported cartridge types :
  * Standard (or plain) cartridge from 8Ko to 64ko
  * Basic cartridge (cartridge written in Basic)
  * Ascii 8 mapper cartridge
  * Ascii 16 mapper cartridge
  * Konami 4 mapper cartridge
  * Konami 5 mapper cartridge **with SCC emulation**
* 64Ko RAM extension
* 64Ko Mapper RAM extension
* SCC without ROM cartridge emulation
* long file / directory name is supported
## Limitations
* rom size is limited to 128Ko due to the limited available RAM of the Pico
* only 14Mo flash memory available
* file (or directory) name is limited to 125 characters
## Usage
1. Connecting Easy Cartridge to a PC with a USB C - USB A cable.
2. Under Windows, an amovable FAT drive named "MSXEASYCART" is added to the PC
3. Copying rom images on the cartridge, on MSXEASYCART drive. It's highly recommanded to organized rom image files in subfolders if there are a lot of rom images.
4. Unmounting the drive MSXEASYCART and disconnect the USB cable
5. Plugging Easy Cartridge to the MSX and powering up the MSX
6. Easy Cartridge built-in rom should start and the user can select a rom image to launch by using a joystick or by using arrow keys, [Space] bar and [Backspace] key of the keyboard.


