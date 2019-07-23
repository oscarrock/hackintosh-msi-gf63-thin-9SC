# hackintosh-msi-gf63-thin-9SC
Setup of hackintosh laptop on this MSI laptop - Intel Core i7 9th Gen

This is my version of a hackintosh setup for this laptop. 
Anyone willing to make this setup to a perfect install is wellcome.

Status:
Succesfull Installed OSX Mojave in a KINGSTON SSD SA400S37120G.

To Do:
1. Intel(R) Wireless-AC 9560 160MHz -> Not compatible (Looking for solutions, because i do not want to modify this neither add a wifi dongle)
2. Intel(R) UHD Graphics 630 -> PNP Device ID	PCI\VEN_8086&DEV_3E9B&SUBSYS_127E1462&REV_00\3&11583659&2&10	
(Is beign recognized but shows 7mb. Maybe this is becouse im still booting with the usb)
3. Realtek High Definition Audio.
4. Hardware monitor installed, for fans, temperature
5. NVIDIA GeForce GTX 1650
6. Realtek PCIe GbE Family Controller -> PCI\VEN_10EC&DEV_8168&SUBSYS_127E1462&REV_15\01000000684CE00000	

Known Bugs:
Random Restarts
No Wifi
No Ethernet
INTEL UHD 630 7mb only


#Laptop Hardware.
https://valid.x86.fr/2463d0

Processor (CPU)
CPU Name	Intel® Core™ i7-9750H CPU @ 2.60GHz
Threading	1 CPU - 6 Core - 12 Threads
Frequency	2094.88 MHz (21 * 99.76 MHz) - Uncore: 3291.9 MHz
Multiplier	Current: 21 / Min: 8 / Max: 45
Architecture	Coffee Lake / Stepping: U0 / Technology: 14 nm
CPUID / Ext.	6.E.A / 6.9E
IA Extensions	MMX, SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, EM64T, VT-x, AES, AVX, AVX2, FMA3
Caches	L1D : 32 KB / L2 : 256 KB / L3 : 12288 KB
Caches Assoc.	L1D : 8-way / L2 : 4-way / L3 : 16-way
Microcode	Rev. 0xAA   ► Spectre (CVE-2017-5715) Patched ◄
TDP / Vcore	45 Watts / 0.957 Volts
Temperature	74 °C / 165 °F
Type	Retail (Stock Frequency : 2600 MHz)
Cores Frequencies	#00: 2094.88 MHz  #01: 3192.19 MHz  #02: 3591.22 MHz  #03: 3192.19 MHz 
#04: 2992.68 MHz  #05: 3491.46 MHz 
Motherboard
Model	MSI MS-16R3
Socket	Socket 1440 FCBGA
North Bridge	Intel Coffee Lake rev 07
South Bridge	Intel HM370 rev 10
BIOS	American Megatrends Inc. E16R3IMS.103 (03/08/2019)
Memory (RAM)
Total Size	16384 MB
Type	Dual Channel (128 bit) DDR4-SDRAM
Frequency	1330.1 MHz (DDR4-2660) - Ratio 1:20
Timings	19-19-19-43-2 (tCAS-tRC-tRP-tRAS-tCR)
Slot #1 Module	Samsung 8192 MB (DDR4-2662) - P/N: M471A1K43CB1-CTD
Slot #2 Module	Samsung 8192 MB (DDR4-2662) - P/N: M471A1K43CB1-CTD
Graphic Card (GPU)
GPU #1 Type	Intel(R) UHD Graphics 630
GPU #1 Brand	Micro-Star International Co. Lt
GPU #2 Type	NVIDIA GeForce GTX 1650
GPU #2 Brand	Micro-Star International Co. Lt
GPU #2 VRAM	4096 MB (Micron)
Storage (HDD/SSD)
Model #1 Name	SAMSUNG MZVLB512HAJQ-00000
Model #1 Capacity	476.9 GiB (~510 GB)
Model #1 Type	Fixed - Bus: NVMe (17)
Model #2 Name	KINGSTON SA400S37120G (FW: SBFKB1E1)
Model #2 Capacity	111.8 GiB (~120 GB)
Model #2 Type	Fixed, SSD - Bus: SATA (11)
Miscellaneous
Windows Version	Microsoft Windows 10 (10.0) Home 64-bit
Windows Subver.	Build 17763
CPU-Z Version	1.89.1 (64 bit)
