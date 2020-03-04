IMPORTANT NOTE: If you are interested to work on this setup i encourage you to install hackintosh (vainilla setup or niresh mojave) and if you have any results i will love to hear about it, please post questions or anything in issues section. Thanks.

# hackintosh-msi-gf63-thin-9SC
Setup of hackintosh laptop on this MSI laptop - Intel Core i7 9th Gen

<h5>Vainilla Catalina on Msi gf63 i7 9750H. Intel UHD 630 </h5>

Hey, just to let you know i got fresh Vainilla Catalina instaled on my lap.
So i wil share with you what i have done. We have a long way to proper setup
and get all working as expected.

#This Laptop Hardware.
https://valid.x86.fr/2463d0

WORKING
- Intel UHD 630 With 1536 MB.
- Audio
- Ethernet
- Wifi (i bought this one, very cheap. and working good. no kext needed its
  compatible with any mac. https://www.tp-link.com/co/home-networking/adapter/tl-wn725n/v3/)
- Battery indicator, and charging.
- Camera

NOT WORKING
- Battery drains fast! (VERY IMPORTANT TO FIX!)
- Fan control ( Heat from the cores!)
- HDMI

I´ll make an step by step for myself and anyone interested in this.

1. FORMAT USB (Disk-Utility osx) 16GB OR GREATHER.
   Format FAT32 - GUID PARTITION MAP.

2. COPY INSTALLER TO USB(TERMINAL)
   sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/USBINSTALLER/

3. Download Clover_v2.5k_r5104.pkg

4. Install clover in EFI of usb.

6. Install Catalalina.

7. Postintall setup: https://www.tonymacx86.com/threads/guide-native-power-management-for-laptops.175801/
sudo pmset -a hibernatemode 0
sudo rm /var/vm/sleepimage
sudo mkdir /var/vm/sleepimage
sudo pmset -a standby 0
sudo pmset -a autopoweroff 0

I am at this point: XCPM only (not so experimental anymore,... it is proven to work)
i tryed with plugin type and got frezes also tryed ssdtPRGen but post says
coffee lake does not need it.

Pending.
Upload benchmark tests

Now i use 2 config.plist for clover just FYI.
config.working.plist > the one that always works for me.
config.plist > the one i change constantly to fix battery and other stuff.

- Attached
Screenshots

Recommended apps.
- Intel power gagdget
- Hackintool

Special thanks to: @jbwharris, @cm0270 and all the people interested in making this setup.
