# micro-bit-to-micro-bit-accelerometer-data-to-unity
the microbits are scripted in c++ using mbed online compiler with DAL library

microbit A will send radio message 'a x y z' where a will be identified as the name of that microbit, x y z are values from built in accelerometer. (wireless)

microbit B will send radio message 'b x y p2' where b will be identified as the name of that microbit, x y are values from built in accelerometer. p2 is a value got from the sensor connected to the microbit's pin2. (wireless)

microbit C will receive radio messages and send it to usb serial port. (connected to usb on laptop)

(if you are using PC just change the port name in unity script to COM 1 or 2 or 3 etc instead)


to compile the script into hex:

step1. go to https://os.mbed.com/users/euxton/code/microbit-dal/ and click import into compiler.

step2. paste the script in the main.cpp file and then click compile to get hex files for your microbits.

step3. drag the hex files into your microbits separately.

if you just want to use the script:
drag and drop the hex files into different microbits.


now when you import the unity package and click play, you can see the messages printed on console.


