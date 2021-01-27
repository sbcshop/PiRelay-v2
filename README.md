# PiRelay-V2
Pi Relay V2 is developed by SB Components with the potential to control 4 appliances and loads up to 240V AC/ 7 A, 125V DC/ 10A to provide a way to control the high voltage/current devices.

<img src="https://cdn.shopify.com/s/files/1/1217/2104/products/4_bc1ba91f-6adc-4aff-a4dd-318e59d422d8_700x.png?v=1603796074" width="300"><img src="https://cdn.shopify.com/s/files/1/1217/2104/products/7_700x.png?v=1603796075" width="300">

### Specification of Pi Relay V2 for Raspberry Pi

* High-quality Relay and loads up to 240VAC/7A, 125VDC/10A.
* Optocoupler 
* Standardized shield shape and design.
* LED working status indicators for each Relay.
* High-quality Relays.
* Pin Stacking Header for accessing GPIO of RPi.

### PinOut

| Relays   | BOARD |    BCM     |
| -------  | ----- | -----------|
| Relay 1  |  35   |   GPIO 19  |
| Relay 2  |  33   |   GPIO 13  |
| Relay 3  |  31   |   GPIO 6  |
| Relay 4  |  29   |   GPIO 5   |

**Steps for PiRelay software installation -**

1. Open Terminal and clone/download the repository by typing below command in terminal: 

   ```
   git clone https://github.com/sbcshop/PiRelay-V2
   
   ```
   
2. Your code will be downloaded to '/home/pi' directory. Use 'ls' command to check the list of directories

3. 'test.py' is example code for PiRelay-V2. Run test file and play with PiRelay


### GPIO 4 Relay Not working Fix

1. Press Start button >> Preferences >> Raspberry Pi Configuration, Then click on Interfaces Tab and make sure 1-Wire is disabled. 
2. Click on OK button then reboot Raspberry pi.

<img src="https://github.com/sbcshop/PiRelay-V2/blob/main/Images/Relay4Fix.PNG"/>
