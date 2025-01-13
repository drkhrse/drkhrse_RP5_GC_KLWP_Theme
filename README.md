# Retroid Pocket 5 GC KLWP Theme
KWLP theme that I built for my black GameCube themed Retroid Pocket 5, although it should work for any 16:9 Android landscape device. The design is inspired by the Settings Cube and Memory Slot management screens on the Gamecube. The first screen, Settings, has apps that can be accessed by clicking on the each section of the cube. The launcher will launch directly into the game launcher of your choice. The memory card screen displays internal (A section) and SD Card (B section) free space in gigabytes. Will require KLWP Pro to import. There are plenty of Global Varibles in the theme to customize the colors of the UI elements. The is an animation of the LED on the GC turning on when unlocking if you decide to use the theme on the home and lockscreen.

For those that want a simpler setup without the Settings Cube screen or animations, there are some alternate wallpaper files included in the \komponents\GCN\Wallpaper folder.

![Screenshot](/screenshots/ss1.png)

Put the included files into your /kustom folder on you device. I installed it on my internal drive so you may need to change the directory paths in the global variables if you put the kustom folder on your SD Card. You will also want to use something like KWGT to add a blank widget to the first screen so that there is no app icons there.

## Optional Files
To fully replicate what I have in my setup you will need to add the following files.

**Fonts** - FOT-RodinProDB-Regular.ttf, FOT-Rodin Pro M.ttf, FOT-RodinPro-B.ttf (These are not free. Add the ttf files into the \kustom\fonts folder. You can use whatever font you want, but these will be the closest to the original GameCube menu font)  
Set the Font, FontLgt, and FontBld global variables with your chosen fonts.

**Icons** - Material Design Icons [here](https://www.reddit.com/r/kustom/comments/fqjx59/misc_material_design_icons_for_kustom_update/)  
These are used for Utility and Application icons. You can use whatever fonticons you want but I used many in this pack.

## Global Variables
**SDPath** = `/storage/####-####` (Set the SDPath global variable to your SD card path for the SD Card space statistics.)

**ClockCol** = `pink, purple, blue, custom` (Pink and purple are the original GC pixel font colors. If you choose custom go into the TimeCol folder and edit TmCust and TmCustS. It is currently set to white)

**GCColor** = `black,indigo` (sets the GC model color on the lockscreen)

The AppSet folder allows you to customize many of the attributes of the app icons that apeear when you select a menu item - size, corner radius, color, etc.

## Settings Cube
You can touch any of the headers in the cube to open on their app section, with the exception of the Launcher on the left side of the cube, which I have defaulted to ES-DE for me. I put alternate images in the \kustom\komponents\GCN\Settings folder for other popular launchers, like Daijisho and Beacon. There are also other alternate labels like Emulation and Streaming if you would prefer to change another category out. The app icons are set to launch my apps of course so you may need to adjust, add or delete apps for your system.

These files are provided as is so unless there are some image bugs I may not be much help since I am new to using KLWP myself. I am also only able to test on the Android 13 with default launcher version that came with the RP5. I have no idea how it would work with other launchers.

Special thanks to all that contribute to the Retroid and overall retro gaming communities.
