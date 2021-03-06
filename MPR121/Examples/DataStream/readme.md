[![Bare Conductive](https://www.dropbox.com/s/p0p71yid2t8tenp/LOGO_256x106.png?dl=1)](http://www.bareconductive.com/)

# Bare Conductive Touch Board Datastream Example

Continuously reads capacitive sense data from the MPR121 on the [Bare Conductive Touch Board](http://www.bareconductive.com/touch-board) and outputs it to the (virtual) serial port. Can optionally interface with Bare Conductive's [MPR121 grapher](https://github.com/BareConductive/mpr121-grapher) or [Max/MSP communication patch](https://github.com/BareConductive/Max-MSP-Touch-Board-communication).

## Requirements

* [Arduino](http://arduino.cc/en/Main/Software) 1.0.5 or 1.5.6+ (1.5.6+ is strongly preferred).

* Arduino's instructions for installing libraries are available [here](http://arduino.cc/en/Guide/Libraries)

* [Bare Conductive MPR121 library](https://github.com/BareConductive/mpr121/)

## Install

This is normally installed as an example within the MPR121 library, but if you want to manually install it into your Arduino sketchbook, here is how to do it.

1. Close the Arduino IDE if you have it open.
1. Download the [.zip](https://github.com/BareConductive/mpr121/archive/public.zip) or clone the repository to your local machine - if downloading the .zip, extract the contents somewhere that suits you.
1. Take the **DataStream** folder and move it to **Arduino Sketchbook Folder**. This will be different for each operating system: 

	**Windows**
	
	Libraries\\Documents\\Arduino
	
	or
	
	My Documents\\Arduino	
	
	**Mac**
	
	Documents/Arduino
	
	**Linux (Ubuntu)**
	
	Home/Arduino


	If this folder does not exist, create it first.
1. Reopen the Arduino IDE - you should now be able to open the sketch in the **File -> Sketchbook** menu.
 

