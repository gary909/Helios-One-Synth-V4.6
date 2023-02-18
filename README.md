"# Helios-One-Synth-V4.6" 

**********************************************************************
**Mozzi Compatability Update** 18/02/2023
The latest version of the Mozzi audio library won't compile with the Helios code or the drone synth code because they've changed the way the filter is named/Implemented.  Instead of downloading the latest version of Mozzi, you'll need an older version, like this one:

https://github.com/sensorium/Mozzi/tree/09ccf15dfbc72aa60c3bca48ac8c8ec081eb57fe

If you've already downloaded the latest version you'll need to go into your Arduino/Libraries folder and delete the Mozzi Folder there.

Click code > download Zip

Go to your downloads folder > find the file and right click > 'extract all' > click 'Extract' (if you get a message about a license click ok).

A new window will open with a file named; 

Mozzi-09ccf15dfbc72aa60c3bca48ac8c8ec081eb57fe 

rename this file to: 

Mozzi-master

Right click on the Mozzi-master file and choose > Send To > Compressed (Zipped) folder

Drag this zipped file into your downloads folder. 

Open the Arduino IDE > Open Sketch > Include Library > Add .ZIP library

Find the Mozzi-Master zipped file in your downloads folder

Hopefully you should get a message saying the library was successfully added.

Restart the Arduino IDE.

You should now be able to upload the code to your Arduino. 

**********************************************************************

-LATEST VERSION- A very easy to build arduino based MIDI controlled synth.

You'll need the arduino MIDI library and Mozzi library.

Now contains the Lazer Engraver file so you can create a front panel.

For full build instructions, see;

https://bloghoskins.blogspot.com/2020/11/20-synth-project-complete-build-guide.html


Code Explanation:

Part 4 - Modulation
https://bloghoskins.blogspot.com/2020/09/helios-one-arduino-synth-part-4-final.html

Previous Parts
Part 3 - Adding a Low Pass Filter
https://bloghoskins.blogspot.com/2020/06/helios-one-arduino-synth-part-3.html

Part 2 - Adding an envelope to our synth
https://bloghoskins.blogspot.com/2020/06/helios-one-arduino-synth-part-2.html

Part 1 - MIDI controlled Oscillator with Wave switch
http://bloghoskins.blogspot.com/2019/07/helios-one-arduino-synth-part-1.html

