## About

This code contains the implementation of automated fingerprint attendance system using nodemcu. The uploaded code is deployed on to nodemcu to Enroll the student fingerprints and then marking their attendance by matching their fingerprint images already stored in the database. Backend code is done in laravel and is uploaded to github by my other group member Huzaifa.


## Installation
You can easily download the ARDUINO IDE editor from the [ARDUINO IDE DOWNLOAD](https://www.arduino.cc/en/software).

After downloading the Arduino IDE, follow  the [Downloading and installing the Arduino IDE](https://docs.arduino.cc/software/ide-v2/tutorials/getting-started/ide-v2-downloading-and-installing) tutorial for more detailed guide on how to install the editor and make it functionable onto your PC.

After the successful installation of the ARDUINO IDE; the next step is to install the necessary libraries for the proper functioning of the IOT components.

Here is how to install software libraries with the new library manager tool in the Arduino IDE [INSTALLING LIBRARIES](https://docs.arduino.cc/software/ide-v2/tutorials/ide-v2-installing-a-library)

After opening the arduino IDE editor for the first time; it will automatically download some basic libraries itself but there are certain libraries that you would need to add manually.

Below are the links to download the required librarires.

https://github.com/adafruit/Adafruit-GFX-Library

https://github.com/adafruit/Adafruit_SSD1306


## Running the code
The next step after you have installed the ARDUINO IDE and the relevent librararies that were mentoned above; is to simply copy the code and paste it on the ARDUINO IDE terminal screen.

Then you have to just click on "debug and run" the code on the editor and thats it.


## Circuit Diagram
Here is the circuit diagram of how to attach the IOT device components correctly in order for the code to work on nodemcu. 

In order for the code to run; remember to first attach the IOT fingerprint to your PC via a data cable and wait for the Nodemcu to blink.

![Fingerprint sensor based bomatric system](https://user-images.githubusercontent.com/113435175/222422457-273a4a64-f0d6-48bf-ba68-143d5488d14e.png)

## Version

Following is the version of Arduino IDE used. 

    Arduino IDE : 2.0.3
   
