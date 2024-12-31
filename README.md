# msx-line-int
MSX BASIC compatible VDP line interrupt routine for V99x8 VDPs.

This example demonstrates how to achieve a simple split-screen effect changing screen colors while the VDP is drawing the screen. Using the same principle, one could achieve more advanced effects like changing screen mode and/or scroll offset mid-screen.

For now, it requires a MSX 2 or superior. This effect can be achieved on TMS9918 based VDPs, but code will be significantly different due it not supporting line interrupts. It probably works on MSX1 containing V99x8 VDPs but most likely needs to be improved due to some MSX2 system variables being used.
