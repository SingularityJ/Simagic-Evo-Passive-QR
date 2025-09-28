# Simagic-Evo-Passive-QR
Simple passive QR for simagic Evo

This is a very simple QR to provide USB passthrough for the EVO bases.

IMPORTANT: the total height of your pcb+pogo pins should be 7.4mm, so if you order 1.6mm pcb, you will need 6mm pogo pins, or you could use 5mm and 3d print a spacer to be exact. both pogo pins and base side pcb are spring loaded so there should be some tolerance, but get as close as possible.

I have included the Gerber .zip and easyeda project file if you want to edit text. pcb doesnt need to be anything special

BOM:
1x    8 pin DIP 2.54mm pitch pogo
1x    xh2.54 4 pin male and female
I buy these: https://a.aliexpress.com/_mqE83nj
get at least 15cm

1x wheel side connector, most likely either xh2.54 or ph2.0

I use a 8 pin pogo, but these aren't available in the software so it is shown as 2x 4 pins, when purchasing make sure the legs are long enough to go through the pcb, mine are slightly recessed which isn't ideal.

You will need to figure out the pinout for your wheel, they are not all the same and dont always follow correct colors. Mixing up d+ and d- wont damage anything but Vcc must be correct or you will fry something. Dan suzuki is building a wheel database, definitely check it out.

I have only been using with my GSI Fpe v2 for months and have had no issues at all even with full led brightness (don't use this as it draws more than simagic rates their base passthrough for) and simagic usb cable, however gsi do good voltage regulation. you may find you need a shorter cable or powered hub if you have voltage drop. i can only test what I have.

as always use at own risk
