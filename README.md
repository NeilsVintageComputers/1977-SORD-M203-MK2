# SORD-M203-COMPUTER
![IMG_1056](https://github.com/user-attachments/assets/09d2c19a-47b3-4e2f-865a-1ca16af44a0c)

Documentation on my Sord M203 MKII computer is a work in progress, there is not much information available on the internet.

I have repaired the floppy controller (a very lossy Tantalum capacitor) and the main board (dirty 4-way dipswitch block) and got it booting on a original 100tpi drive and a disk supplied by Franck. 

The drives (and disks)  it came with when I obtained it were 96TPI 80Track drives, 
I now have these working and discovered quite a lot of games and other programs on the disks, but a lot of them appear too large to fit in the available memory once Basic takes up most of it.

During this process I had quite a lot of 5.25" floppys fail and thought I should come up with a alternative in case there may be a time in the future when I have no working 5.25" floppys.  
I hope to get a Gotek/FF working eventually, but as a quick solution (in case I ran out of working 5.25" floppys) decided to get a pair of 3.5" drives working.  The drives are 720K drives from a Amstrad PPC512, the only mods needed was to swap pins 6 and 34. I copied the images I had made with the Greaseweazle to them and they worked.

Currently I am trying to get a original 100TPI drive to coexist on the same cable with a 96TPI drive so as to convert the disks to the original Sord format.

No success yet, the 96TPI drives have pins 34 and 6 swapped so the function of each pin is the same as the 100tpi drives.

I think the problem could be the terminator on the 100TPI drive biases the lines via 330/220R resistor divider where the 96TPI drives pulls them up to 5V via 150R resistors. I have tried all combinations of terminators with no success.

To be continued......
