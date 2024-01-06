# HEX_40106_Video_Synth
A CHA/V based video synth

This is my take on the Jonas Bers' CHA/V video synth (https://jonasbers.com/chav/).
Here I am using this type of VGA test signal generator: https://es.aliexpress.com/item/33056599680.html

C1 to C6 are timing caps; the values can be changed for obtaining different frequency ranges. For example, I have also used C1=1nF, C2=47nF, C3=100nF, C4=3.3uF, C5=33uF, C6=220uF in my second build. C8 to C13 are coupling caps, and can be also changed. For example, I have used 220nF caps in my second build. As stated in Jonas Bers' web: Experiment!
The VGA test signal generator is cyanoacrylate-glued to the PCB after doing the corresponding wire connections (see pics 5, 6 and 7).

A synth video-demo will be available soon!

![alt text](https://github.com/SlowProject/HEX_40106_Video_Synth/blob/main/pics/videosynth9.jpg)
NOTE: In the prototype I show in the pics, the labels "sync" and "out" of the jacks are swapped. This mistake has been corrected in the Gerber file uploaded (Gerber_PCB_OSC BANK 40106 HEX-VIDEO SYNTHvs3).
