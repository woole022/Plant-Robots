# Adafruit_Seesaw
Arduino driver for seesaw multi-use chip

Check out the [documentation](https://adafruit.github.io/Adafruit_Seesaw/html/class_adafruit__seesaw.html) for a listing and explanation of the available methods!

# What we're doing here

Basically, this was a C++ library that worked with the Arduino, that we're either adapting to the PIC24, or stealing all of it's secrets, and building it from scratch for the PIC24. What I did to start was I changed all the file names from .cpp to .c, this means they don't work, this also means that C++ code will give you those delicious compiler errors which you will need to rewrite it for C for the PIC24
