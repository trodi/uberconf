# hardware hacking

biochip in farm animals transponders to connect them to the internet

## raspberryPi
* SoC = system on a chip, ARM based
* not normally used to connect to other sensors (unbuffered GI ports)
* runs linux, java, javascript!
* (made airplay server to run XBMC)
* limitations
	* no analog inputs
	* few digital inputs
	* can't be battery operated practically
	* limited horsepower
### cool projects
* xbmc
* kiosk
* web/application server

## arduino
* super low power
* excellent buffered i/o ports
* open source hardware
* shields = snap-on addons
	* TinkerKit
	* shields are expensive
### android + arduino
* can get a cheap android device for all the sensors instead of extra shields
* should work on nexus 7 too (can get $25 tablets too)
* firmata - can program arduino with other langs via this protocol
	* tell board what to do and grab sensor input from board via your program running on pc etc.
	* https://github.com/firmata/arduino
	* push standard firmata to board
* https://www.sparkfun.com/