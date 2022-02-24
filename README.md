Remote SSPA

The goal is to be able to run a SSPA remotely (currently to the counterpoise of my dish in my case) and to get the collected informations to a PC or Rapasberry PI in a JSON format to be able to view it from a webpage for example.

The informations are :
- Main DC voltage (50V/28V/...)
- Main DC current
- Temperature on the mosfet board
- Temporateur on the SSPA box
- Forwarded RF
- Reflected RF


Materials I used :
- 1 * Arduino NANO 3 https://www.amazon.com/HiLetgo-ATmega328P-Controller-Development-Unsoldered/dp/B01DLIJQA2/ref=sr_1_2_sspa
- 2 * Temperature sensor https://fr.aliexpress.com/item/4000139863432.html
- 2 * GY-159 Current sensor : https://fr.aliexpress.com/item/32707240446.html
- 1 * RF Bi-directionnal Coupler depending of power/frequency (you can find NARDA refurbished on ebay)
- 2 * 20db/10dB depending of your RF coupler
- 2 * AD8361 RF detector https://fr.aliexpress.com/item/32854965471.html
