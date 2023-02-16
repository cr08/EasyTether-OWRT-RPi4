# EasyTether-OWRT-RPi4
Reverse engineer/rebuild of the OpenWRT packages for EasyTether for a modern Raspberry Pi 4 Model B - WIP as of this writing

## Goals
1. Make the EasyTether 'drivers' usable on the Raspberry Pi 4 running OpenWRT. So far it has been confirmed to work fine on the latest OpenWRT builds on earlier Pi models where ET has explicit support. I have also been able to get the `easytether-usb` executable to run on the Pi 4 running the latest table OpenWRT as of this writing. Likely just a simple packaging change will be needed to make it plug and play.
2. Attempt to make it work with multiple devices/phones simultaneously. At the current point in time it only seems to work with just one phone at a time. The `easytether-usb` executable has some command line options that, in theory, would enable separate devices and interface names to be used. More testing needs to be done here.
