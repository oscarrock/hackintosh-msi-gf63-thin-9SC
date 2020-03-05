# hackintosh-msi-gf63-thin-9SC
Setup of hackintosh laptop on this MSI laptop - Intel Core i7 9th Gen

<h5>Vainilla Catalina on Msi gf63 i7 9750H. Intel UHD 630 </h5>

Hey, just to let you know i got fresh Vainilla Catalina instaled on my lap.
So i wil share with you what i have done. We have a long way to proper setup
and get all working as expected.

#This Laptop Hardware.
https://valid.x86.fr/2463d0

WORKING
- Intel UHD 630 With 2048 MB.
- Audio
- Ethernet
- Wifi (i bought this one, very cheap. and working good. no kext needed its
  compatible with any mac. https://www.tp-link.com/co/home-networking/adapter/tl-wn725n/v3/)
- Battery indicator, and charging.
- Camera
- Temperature seems right no heat.
- Kingston SSD (Working fine)

NOT WORKING
- Battery (Seems to work ok. but i have not tested fully)
- HDMI
- Touchpad (Touchpad is working but it has no scrolling with two fingers.)
- SAMSUNG MZVLB512HAJQ - DOES NOT WORK WITH MAC
  found a posible workaround here:
  https://www.tonymacx86.com/threads/guide-hackrnvmefamily-co-existence-with-ionvmefamily-using-class-code-spoof.210316/
  https://www.tonymacx86.com/threads/mojave-install-panic-on-dell-xps-9570-with-samsung-mzvlb512hajq-pm981.268172/
  https://www.tonymacx86.com/threads/how-to-fix-pm981-in-10-13-3-17d47.245063/

I´ll make an step by step for myself and anyone interested in this.

1. FORMAT USB (Disk-Utility osx) 16GB OR GREATHER.
   Format FAT32 - GUID PARTITION MAP.

2. COPY INSTALLER TO USB(TERMINAL)
   sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/USBINSTALLER/
   The Installer was downloaded from Mac App Store.

3. Download Clover_v2.5k_r5104.pkg

4. Install clover in EFI of usb.

6. Install Catalalina.

- Attached
Screenshots

Recommended apps.
- Intel power gagdget
- Hackintool

https://www.tonymacx86.com/threads/guide-hackrnvmefamily-co-existence-with-ionvmefamily-using-class-code-spoof.210316/

Special thanks to: tonymacx86. RehabMan.
Also @jbwharris, @cm0270 and all the people interested in making this setup
