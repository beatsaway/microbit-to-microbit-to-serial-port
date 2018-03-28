# micro-bit-to-micro-bit-accelerometer-data-to-unity
the microbits are scripted in c++ using mbed online compiler with DAL library


this project is to send accelerometer x y z value from microbit a(wireless) to microbit b(usb connected) as a one line message, then send the message from microbit b to unity

(if you are using PC just change the port name in unity script to COM 1 or 2 or 3 etc instead)


if you want to be able to compile the script:

step1. go to https://os.mbed.com/users/euxton/code/microbit-dal/ and click import into compiler.

step2. paste the script in the main.cpp file and then click compile to get hex files for your microbits.

step3. drag the hex files into your microbits separately.

if you just want to use the script:
drag and drop the hex files into different microbits.


now when you import the unity package and click play, you can see the message printed on console.


