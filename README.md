# Microchip-s-EBI-incremented-via-DMA
This C file as demonstrated on YouTube shows how I use the DMA to increment my 24 bit EBI (External Bus Interface).
The EBI is used as the address pins on 512k 16 bit ISSI SRAM.
It’s a big file since it includes large fonts to display time on a 5” SSD1963 16 bit colour screen.
In this original file, I capture a large section of the screen, store the image to a large buffer then read it back to a buffer before displaying it.
I use the DMA to increment the address since trying other methods would not work.
In later revisions, to follow, I reversed the read and write pins on the SRAM so no additional buffers are required.

