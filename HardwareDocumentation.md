
# Wave Hardware Documentation #
... a lot of links should be added here ... some info extracted from some XDA threads...
The idea is to achieve [something like this page which is for GT-S5620](http://code.google.com/p/mondroid/wiki/Hardware)

Related XDA threads:

[http://forum.xda-developers.com/showthread.php?t=901416
internal Documents, Videos etc. around S8500/S8530 and little bada]

[http://forum.xda-developers.com/showthread.php?t=1012856
DEV The project to port Android(froyo) on S8500 (8530)]

[DEV S8530 open](http://forum.xda-developers.com/showthread.php?t=1245874)

## Service Manuals ##
They are in several threads ...



## Power Management ##
S8500: Maxim MAX8998

S8530: Maxim MAX8997

## Touchscreen Sensor ##
ATMEL MXT224

http://www.alldatasheet.es/datasheet-pdf/pdf/313246/ATMEL/MXT224.html

## Display Driver ##
S8500: TL2796

S8530: LG4573

Related XDA threads:
[documentation about S8530 lcd panel](http://forum.xda-developers.com/showthread.php?t=1245998)

## Processor ##

Samsung S5PC110A01

ARM v7 Processor rev 2 (v7)

## Memory ##

s8500 have 2GB moviNAND and 512MB oneNAND

S8500 and S8530 are similar to I9000, but they have less physical RAM

S8500 have ONLY 128+256=384MB RAM memory (Galaxy S have 512MB).

### moviNAND ###

S8500: has KLM2G1DEDD 2GB MLC NAND, partitioned

S8530: Sandisk SDIN5D2-2G

Info:

[KLM2G1DEDD-A101... and the other Memory Chips](http://forum.xda-developers.com/showthread.php?t=899661)

http://forum.xda-developers.com/showthread.php?t=1012856&page=4

[S8530, Wave II internal Pictures](http://forum.xda-developers.com/showthread.php?t=996350)

## Sound ##
WM8994 Wolfson microelectronics Multi-Channel Audio Hub CODEC for Smartphones

http://www.wolfsonmicro.com/products/audio_hubs/WM8994/

http://mr2857gb.googlecode.com/svn/trunk/data%20sheet/codec/WM8994_Rev3.0.pdf

## Connectivity ##
### Wifi and bluetooth ###
Broadcom BCM4329: Low-Power 802.11n with Bluetooth 2.1 + EDR and FM (Tx and Rx)

http://www.broadcom.com/products/Bluetooth/Bluetooth-RF-Silicon-and-Software-Solutions/BCM4329

Samsung SWB-B23 Broadcom BCM4329 WLAN+BT Solution

http://mr2857gb.googlecode.com/svn/trunk/data%20sheet/wifi/SWB-B23_DS_Datasheet_rev7.pdf

Broadcom uses configuration files:
  * Bada: Stune /SystemFS/Drivers, Wlan\_bcm4329\_rte.txt / Wlan\_bcm4329\_mfg.txt / Wlan\_SWB-B23\_mfg.txt / Wlan\_SWB-B23\_mfg.txt
  * Badadroid: /system/vendor/firmware nvram\_net.txt, https://github.com/Rebell/android_device_samsung_wave/tree/jellybean/prebuilt nvram\_net\_s8500.txt , nvram\_net\_s8530.txt

### Radio GSM, UMTS ... ###
Qualcomm QSC6270 :Single-chip solution for HSDPA and WCDMA (UMTS) networks

http://www.ic-on-line.cn/view_download.php?id=1169415&file=0098\qsc6270_1011529.pdf

Triquint Semi TQM7M5012H : 3V Quad-Band GSM850/GSM900/DCS/PCS Power Amplifier Module

http://www.triquint.com/products/p/TQM7M5012

Skyworks SKY77195 : Dual-Band PA Module for WCDMA / HSDPA Band I (1920-1980 MHz) and Band VIII (880-915 MHz)

http://www.skyworksinc.com/Product.aspx?ProductID=598

## Sensors ##
### Proximity sensor ###
GP2A Proximity Sensor, Sharp

### Magnetic field sensor ###
Asahi Kasei Microdevices AK8973:3-axis Magnetic field sensor
http://www.droid-developers.org/images/b/b2/AK8973.pdf