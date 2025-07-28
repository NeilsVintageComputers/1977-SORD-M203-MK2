# SORD-M203-COMPUTER
![IMG_1056](https://github.com/user-attachments/assets/09d2c19a-47b3-4e2f-865a-1ca16af44a0c)

![With96tpiDrives](https://github.com/user-attachments/assets/5aa4f8f2-0a94-4257-ac67-0279ce7a4371)


Documentation on my Sord M203 MKII computer is a work in progress, there is not much information available on the internet so this may help others trying to get a Sord working.

When I first tried it there was nothing on the screen 9 out of 10 turn ons, this was fixed after flipping the 4-way dip swith block switches back and forth a few times after trying to squirt some contact cleaner into it. This fault may also have been partly due to capacitors needing to reform after years of no use.  It now started up reliably.

The machine wouldnt boot the disks that it came with, I didn't know if the disks were faulty or if there was a hardware fault.

A friend put a message on facebook for me and Franck replied, he sent me a boot disk all the way from France. Many thanks to him.
They were in original 100tpi format, I had 2 of these drives that I had found many years ago before getting the Sord computer, I repaired one of them and could now back up the disks from Franck with my Greaseweazle.
I tried booting the computer with this drive but it didn't seem to be reading the disk, the same problem I had encountered when using the 96tpi drives and disks the computer had come with. 
There was a hardware fault, likely with the controller, the drive was turning on but no data was being read.
I noticed the controller had a lot of tantalum capacitors on it, without having a schematic I decided to remove and test each caoacitor.
Most were ok but there were a couple of very lossy ones.
With these replaced the computer booted up!

The drives and disks it came with were 96TPI 80Track drives, I now have these working and discovered quite a lot of games and other programs on the disks. Most of them appear too large to fit in the available memory once Basic takes up most of it, but I managed to load and run a few of them.

During this process I had quite a lot of 5.25" floppys fail and thought I should come up with a alternative in case there may be a time in the future when I have no working 5.25" floppys!  
I hope to get a Gotek/FF working eventually, but as a quick solution (in case I ran out of working 5.25" floppys) decided to get a pair of 3.5" drives working.  The drives are 720K drives from a Amstrad PPC512, the only mod needed was to swap pins 6 and 34. I copied the images I had made with the Greaseweazle to them and they worked.

Currently I am trying to get a original 100TPI drive to coexist on the same cable with a 96TPI drive so as to convert the 96tpi disks to the original Sord 100tpi format.

No success yet, the 96TPI drives have pins 34 and 6 swapped so the function of each pin is the same as the 100tpi drives.
I think the problem could be the terminators, the terminator on the 100TPI drive biases the lines via 330/220R resistor divider where the 96TPI drives pulls them up to 5V via 150R resistors. I have tried all combinations of terminators with no success.

To be continued......
