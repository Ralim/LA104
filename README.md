# LA104 Logic Analyser 

This is a firmware fork from the origional firmware.
Sadly this will require building in IAR so I will aim to upload releases fairly often.
I'm using IAR 4.6 locally.

## Features Added / Changed

* Speed up boot screen to minimal time
* Hold K3 and use the A wheel to adjust X pos
* Hold K3 and use the B wheel to adjust time base
* Hold K4 and use the B wheel to smart move the selected time menu item
* Press K4 with no menu entered to cycle which time menu item is selected



## Notes for use

If you press K4 (OK) while the system is waiting for a capture, it will trigger the output mode to send data out the P pins

You can connect to SWD through the USB port if you wire up D+ to SWDIO (Green USB) and D- to SWCLK (White USB).

