# Soldering Report

1. Through-Hole Components (THT)

I already had good experience with this type of soldering. Because of this, I worked fast. I started with the smallest components first, then the microcontroller, and finally the connectors. On some pins, especially on the main connectors, I went a bit too fast and put a little less solder than I should. But I checked everything at the end, and the connections worked perfectly in the tests. Of course, I still need to touch them up to fix them properly.

2. Surface-Mount Components (SMD)

I followed a simple rule: I soldered the bigger components first, and the smaller components at the end. This is better for SMD because the PCB is really small, and it is more difficult to solder big components (like the microcontroller, for example) if we already have other pieces soldered nearby. Finally, I turned the board over and soldered the through-hole parts, which were the connector pins.

I had done this before, but SMD soldering is always more difficult for me. When I was soldering the main chip, I accidentally made some solder bridges. To fix this, I used a copper desoldering wire (solder wick) to remove the extra metal, and then I did it again carefully. I tried to change the tip of my soldering iron to a smaller one, but it did not help, so I went back to my usual soldering tip.

The crystal oscillator and the small capacitors (0603 size) were also very hard to solder. The capacitors, for example, are very small and tall relative to their footprint. It was difficult to make them touch the board pads correctly. I used tweezers to hold them down, put solder on one side first to stick them, and then soldered the other side.

3. Final Testing

At the end, I performed a continuity test using a multimeter to check all the connections. I checked if there were any short circuits between RAW, VCC, and GND. I also checked if the chip pins were well separated and isolated. Everything passed the test and worked great. We also test the PCB with a bootloader and a small program for see if everything is working great.

4. Commentaries

It was a great experience! The whole team was there to help and explain what we should do, as well as to evaluate us and give feedback. Good soldering is really important for any electronics module. Also, using the practice SMD board was really useful for practicing before starting on the real one.