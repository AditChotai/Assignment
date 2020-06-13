# Simple Relay Control Via Serial
Documentation by Orwa

## Components
1. Hardware<br />
2. relay_sketch.ino<br />
3. relay.py<br />
## Wiring Diagram
&nbsp; ![wiring Diagram](https://github.com/AditChotai/Assignment/blob/master/Img/Wiring%20Diagram.png)

## Prerequisites (installation)
1.	PySerial package. To install, type the following from the command prompt:<br />
    “pip install pyserial”
    
## Usage instructions (as a library)
1.	Launch “idle” on windows<br />
2.	Type: “import os;print(os.getcwd())”<br />
![screenshot](https://github.com/AditChotai/Assignment/blob/master/Img/2.png)<br />
3.  Copy “relay.py” to subdirectory “Lib” within the folder above (displayed in idle in blue)<br />
4.	Now you can use the library using “import relay” then calling the following functions:<br />
&nbsp; a.	relay.turn_on(): turns the relay on<br />
&nbsp; b.	relay.turn_off(): turns the relay off<br />
5.	Note that if the hardware is not connected, then an exception will be thrown when importing the library<br />
6.	Note that if the hardware is connected but being used by another program, an exception will also be thrown when importing the library

## Usage instructions (from the command line)
1.	To turn on the relay from the command line, go to the folder where “relay.py” is stored and type the following commands:<br />
&nbsp;  a.	“python relay.py 1” turns the relay on<br />
&nbsp;  b.  “python relay.py 0” turns the relay off<br />
2.	Note that if the hardware is not connected, an error message will be displayed.<br />
3.	Note that if the hardware is connected but being used by another program, an error message will be displayed
