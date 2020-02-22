# Mayumi_v4
Mayumi v4 PS1 Modchip. Often I find just modder to sell their chips and don't show how to programm them on your own.
Sadly, the original website http://syste.ms/~mayumi/ is no longer online.

![Screenshot of Website](/images/original_website.PNG)

Most modders will use the old hex files from the year 2000. I could not find any source codes.
So I dumped the old website and will share all the old information I found.

## PIC Microcontroller
* Microchip PIC12F508 (newer version of PIC12C508)

## Tools needed
* PICkit 3
* SOP8 to DIP8 adapter (pitch: 1.27mm, often labled as "e")

## Connecting the PIC

* PICKit 1 ⟷ IC 4 (VPP)
* PICKit 2 ⟷ IC 1 (VDD)
* PICKit 3 ⟷ IC 8 (VSS)
* PICKit 4 ⟷ IC 7 (ICSPDAT)
* PICKit 5 ⟷ IC 6 (ICSPCLK)

![Connect the PIC](/images/pickit-to-12f508.jpg)

## Supply Voltage (VDD)

See page 72.

| Min   | Max   |
|-------|-------|
| 2.2 V | 5.5 V |
