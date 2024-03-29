# Tana58

Handwired 58 key wireless split keyboard powered by ZMK

![alt text](https://github.com/SDodding/tana58/blob/main/images/tana58_3.jpg?raw=true)

Interesting files:

- What passes for a wiring diagram in /images
- STL files for 3d printing in /stls (There's only the left side, so you'll want to print a mirrored set)
- Freecad files if you wish to modify this for yourself, or for use with other components

Firmware for this board can be found [here](https://github.com/SDodding/tana58_zmk/tree/main)

BOM:

1. 2x Nice!Nano controllers or compatible. I used some Supermini NRF52840 Nice!Nano compatibles from aliexpress. I have since replaced them with proper Nice!Nanos however for better battery life and purchased them from [splitkb.com](https://splitkb.com/products/nice-nano).
2. 2x Mill Max low profile sockets (Mill Max 315-43-112-41-003000) with pins (Mill Max 3320-0-00-15-00-00-03-0). I used [these](https://splitkb.com/products/mill-max-low-profile-sockets?variant=31945995845709) from splitkb.com
3. 2x PCB grid boards that you don't mind chopping to size and drilling a hole through to mount on the controller bracket. I used some like [this](https://www.amazon.nl/-/en/gp/product/B07V39NT2Z) from Amazon and scored them carefully with a stanely knife before breaking them.
4. 58x MX Switches
5. 58x MX Keycaps. I used DSA caps from [spkeyboards.com](https://spkeyboards.com/pages/dsa-profile)
6. 58x THT signal diodes. I used [these](https://splitkb.com/products/tht-diodes) from splitkb.com (1N4148 Signal Diode)
7. 2x Reset switches. I used [these](https://splitkb.com/products/reset-buttons) from splitkb.com (SKHLLCA010). These were glued in to the support bracket in the model
8. 2x power switches.  
 I repurposed some three position ON-OFF-ON (SS 25539 N) switches for this from [Reichelt](https://www.reichelt.nl/nl/en/slide-switch-angled-pitch-5-08-1-x-on-off-on-ss-25539-n-p105722.html). The 3d model is set such that the second on position is physically blocked so that it acts only as a two position switch. You could follow this part, or update the bracket it's glued into in the freecad model for whatever you'd rather use.
9. 22x M2 threaded heat set inserts
10. 22x M2x8 screws
11. 2x 3.7v Lithium Polymer batteries with JST connector. I used some small 150mah ones from [Kiwi Electronics](https://www.kiwi-electronics.com/en/lithium-polymer-li-po-battery-3-7v-150mah-3459). I would say that there is a lot of room in the keyboard though due to the tenting, so you could easily fit 1200mah batteries (or larger) inside.
12. 2x Male JST-PH2.0 connectors. Do ensure the wire colours match the battery connectors before using any you buy. I bought some off Amazon and the connectors originally connected red to black and black to red...

Of course ALWAYS check the battery with a multimeter before connecting it to ensure the polarity is as expected.
