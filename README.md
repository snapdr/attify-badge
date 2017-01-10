# attify-badge
Attify Badge GUI tool to interact over UART, SPI, JTAG, GPIO etc. 

The first build of the tool will focus only on linux.
The GUI will be built using PyQt4 and python2.
We intend to make the tool cross platform eventually.

Okay, so following @Arun Mangesh's advice, I rewrote the tool in python2 and Qt4. main.py got a little buggy along the way. For now I removed the Run-Baudrate.py function due to the long processing time and incorrect results that I seem to be getting, I'll add it again once I figure out what went wrong with it. ( Right now it just keeps showing 115200 as the baud rate on every device) 

Also i was unable to run Adafruit's FT232H library because the two modules required to run the scripts keep getting installed on different versions of python. Its probably a swig related error, I just posted the issue on their github page. 
I will have to rewrite the code for the GPIO tab with Adafruit's libraries once i get them working.
The bugs will be fixed! 

Run main.py!  
