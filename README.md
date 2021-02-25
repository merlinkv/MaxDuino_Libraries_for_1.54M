

# LiquidCrystal_I2C Advise #
LiquidCrystal_I2C Library has been modified by droman to allow the use of lcd.begin(); or lcd.init(); to initialize LCD screens.

Now, you can use one or other command.

# Installation #
Unzip the file "LiquidCrystal_I2C.zip" under the folder named "libraries" in your Arduino sketchbook folder.
Create the folder "libraries" in case it does not exist yet. Now you can see all files inside the new
LiquidCrystal_I2C folder. Do the same with SdFat.zip, TimerOne.zip & TMRpcm.zip.

# Usage #
To use the library in your own sketch, select it from *Sketch > Import Library*.

# IMPORTANT ADVISE #

The next steps really aren't needed but maybe can solve issues reported by some users.

I have included two new files "Arduino_Libraries.zip" & "Arduino_Libraries_Sketch_Folder.zip"

These zip files include all my working libraries.

1) Close Arduino IDE
2) Go to the Arduino\libraries folder & delete all contents
3) Unzip "Arduino_Libraries.zip" in the Arduino\libraries folder
4) Now you can see inside many new folders
5) Go to your sketch folder, by default ..\Documents\libraries folder & delete all contents
6) Unzip "Arduino_Libraries_Sketch_Folder.zip" in the sketch folder. Remember, by default ..\Documents\libraries
7) Again, you can see inside many new folders.
8) Start Arduino IDE
9) Try to compile MegaDuino Firmware, it must work OK !!!!!
10) Enjoy!

