# micro-bit-to-micro-bit-accelerometer-data-to-unity
the microbits are scripted in c++ using mbed online compiler with DAL library


this project is to send accelerometer x y z value from microbit a(wireless) to microbit b(usb connected) as a one line message, then send the message from microbit b to unity

(if you are using PC just change the port name in unity script to COM 1 or 2 or 3 etc instead)


if you want to be able to view/edit the script:

step1. go to https://os.mbed.com/users/euxton/code/microbit-dal/   and click import into compiler.

step2. paste the MicroBitSender/MicroBitReceiver script in the main.cpp file and then click compile to get hex files for your microbits.

step3. go to unity, choose edit>project setting>player then change to Net 2.0 instead of Net 2.0 sub

step4. create a script in unity and paste the attached script.



if you just want to use the script:
drag and drop the hex files into 2 different microbits.
