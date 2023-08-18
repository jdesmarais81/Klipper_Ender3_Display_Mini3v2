# Klipper Ender3_Display_Mini3v2
This is the print config file for Klipper to work with an Ender 3 using a bigtreetech mini 3 v2 board and a rpi3


The original file can be [found here](https://gist.github.com/arabisaldrin/502a73786fe1e7af83754a0be07949a3), but the menu system didn't work, it seems like it was made for an older version of Klipper

The top part is settings I found for the ender 3 and bigtreetech skr mini e3 v2 default printer.cfg

## Parts Required
- Ender 3 (Original)
- BigTreeTech SKR Mini 3 v2 (*it may work on other version but I can't test that*)
- Raspberry PI 3/4 Running Klipper (*I used [Kiauh](https://github.com/dw-0/kiauh) for the install*)
- MainSail is installed as well

## Basic Printer Config
**Ender 3 (Original)** 

Use **basic_printer.cfg** if you do not want to use the display and you want to use USB to RPI


## To Use

Download the cfg file you want to try, rename it to printer.cfg and upload it to MainSail, restart klipper
