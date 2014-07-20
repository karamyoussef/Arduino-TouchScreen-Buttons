Arduino-TouchScreen-Buttons
===========================

Library for drawing buttons to the Seeed Studio TFT touch screen


Introduction:
This is a library created for the Arduino Uno and Seeed Studio TFT touch screen (Version 1).  The user can create buttons
for the touch screen by creating Button instances.  For example:

Button button1(x, y, width, height, borderColor, fillColor);

Note that the x, y, width and height parameters are ints.  The code assumes the provided values are valid.  In other words,
the values are not negative and the button occurs within the confines of the touch screen (0 < x < 240) and (0 < y < 320).
The borderColor and fillColor choices are RED, BLACK, GREEN, BLUE, CYAN, YELLOW, WHITE and GRAY1.

Required Files:
I assume you have all the neccessary libraries to run basic programs on the Seeed Studio Touch Screen.  However, note
that that the following custom library is required.  Search Github for my custom library.

(1) TouchScreenGeometry

Documentatation:
The code was thoroghly documented using DOxygen. Please see the HTML folder for detailed code documentation.

Bugs:
There are no known bugs at this time.  If you see any bugs, please contact me and I will do my best to resolve them.
You may also feel free to resolve them yourself.  Just check with me before you submit any updates.

Upgrades:
We become better programmers by always looking for ways to improve our code.  Thus, I will always look for ways to improve
this code.  If you have any suggestions for improve or would like to make improvements yourself, please let me know.
