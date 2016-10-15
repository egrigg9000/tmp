Changes for 10-15-16

1. The design now works for the DS18B20 and not the TMP35. The DS18B20 is a digital sensor with increased accuracy. It does not have the issue where the readings vary widely on battery versus USB power to the board. Recommended purchase the waterproof version at this link: https://www.sparkfun.com/products/11050
2. Development environment changes include Arduino version 1.6.12 which is optimized for Safari. The latest AVR board code works for the RedBoard / Ardruino Uno which is what is being used for this prototype, currently at 1.6.14. (Reports of earlier incompatibility should be ignored).
3. Updated diagram showing most of the previous wiring used for the TMP35 implementation is preserved. The diagram shows the DS18B20 wired into available power, digital, and ground slots, and the TMP35 is removed.
4. Code is a direct copy from the ameyer example on bildr, except for modifications as noted in the comments. The LCD code is added in from the TMP35 implementation, most of which came from the spark fun LCD tutorial. The trick is merging these two together but that seems to have gone without a hitch. Link to ameyer code:
http://bildr.org/2011/07/ds18b20-arduino/
5. Please note comment thread on above is not actionable. Nothing to see there.