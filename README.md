# micro-bit-to-micro-bit-accelerometer-data-to-unity
These micro-bit scripts and the unity package is for the 2018DMSP project. 
https://dmsp.digital.eca.ed.ac.uk/blog/multidimensionalobjects2018/

The microbits are scripted in c++ using mbed online compiler with DAL library.

Microbit A script can be compiled on microbit(s) that send radio message 'a x y z' where a will be identified as the name of that microbit, x y z are values from built in accelerometer. (wireless)

Microbit B script can be compiled on microbit(s) that send radio message 'b x y p2' where b will be identified as the name of that microbit, x y are values from built in accelerometer. p2 is a value got from the sensor connected to the microbit's pin2. (wireless)

Microbit C script can be compiled on microbit(s) that are connected to a USB port. It will receive radio messages, which are being forwarded to the connected usb serial port. (connected to usb on laptop)

To compile the microbit script:

step1. go to https://os.mbed.com/users/euxton/code/microbit-dal/ and click import into compiler.

step2. paste the script in the main.cpp file and then click compile to get hex files for your microbits.

step3. drag the hex files into your microbits drive folder separately.

When you import the unity package into Unity and click play, you can check messages received on console.
(if you are using PC just change the port name in unity script to COM 1 or 2 or 3 etc instead)



