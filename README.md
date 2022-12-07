# OpenCore 0.8.7 for asus z87-a with intel core i7-4770K
#
#                                                Specifications of my equipment
* Processor - Intel Core i7-4770K
*
* Motherboard - ASUS Z87-A
*
* Video card:
* * (iGPU) - Intel HD 4600
* * (dGPU) - SAPPHIRE NITRO+ Radeon RX 590
*
* Network:
* * Ethernet Chipset - Realtek 8111GR
* * WI-FI + Bluetooth - FV-HB1200
*
* Сpu cooler - SNOWMAN MX6
*
* Sound chip - Realtek ALC892
*
* Storage:
* * SSDPR-CX400-128-G2 Media - Main
* * WDC WD5000AAKS-00UU3A0 Media
*
* Memory:
* * Samsung M378B5773DH0-CH9 DDR3, 4 GB, 2133 MHz, 13-15-15-28 - My overclocking
* * Patriot PSD34G16002 DDR3, 8 GB, 2133 MHz, 13-15-15-28 - My overclocking
*
* I am currently using the system - Ventura 13.0.1 (22A400)

# My notes
* In my setup, I have an overclocked CPU and RAM. My processor is overclocked to 4.4 MHz. I wrote about RAM in the specification.
*
* There will be two versions of the bootloader - with and without iGPU gravity.
*
* I will remove my individual settings for overclocking in order to avoid conflicts with you.
*
* Please note that Haswell's GPU does not work on systems above Monterey.
*
* With graphics iGPU - SMBIOS iMac15,1
* Without graphics iGPU - SMBIOS MacPro7,1
*
* WI-FI + Bluetooth - FV-HB1200 - For this hardware I will leave the AirportBrcmFixup.kext as well as the option in the bootloader "ExtendBTFeatureFlags". If you do not have this equipment or it is different - see various instructions on the Internet for proper configuration
