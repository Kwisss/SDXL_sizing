## SDXL_sizing-with-inpaint 

I wanted to make an inpainting example with Automatic Sizing for SDXL 
Automatic Sizing for SDXL takes the native resolution, aspect ratio, and original resolution. It uses these to calculate and output the generation dimensions in an appropriate bucketed resolution with 64-multiples. 

the original repository for that is here: https://github.com/Ser-Hilary/SDXL_sizing

The only downside is that it takes the resolution as a string, so I made a node to concat 2 integers to a string with a "x" in the middle.

The Idea Behind this whole fork is that I hope we can can convince Ser-hilary to make the extra node obsolete,
By using 2 integers.(or worst case a tuple), instead of a string


I think with this idea he/she is really on to something, so I wanted to share some examples here and help it gain some tracktion.
