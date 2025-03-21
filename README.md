# do52pro reverse engineered

You may have seen the split keyboard do42 / do52 / do52 pro on aliexpress

## go to the wiki

https://github.com/ilfmoussa/do52pro/wiki

## Don't buy IT!!!
Let me explain, you will pay about 50$ (or euros)... for:
- 2 pcb (the same for left and right)
- plastics for the keyboard
- 2 (3d) printed sticks (ugly)
- 2 DPAD
- 1 trackpoint
- 3 resistors (2 x 4.7kOhms and 1x 100kOhms)
- 1 capacitor (2.2uF)
- screws
- 52 diodes 1N4148 (I thinks)
- 2 jack

=> a precompiled firmware (if you ask the vendor, that's all you will get) for arduino micro 32u4 (usb lib) (I think also)

And no assembly guide, no datasheets, no switch , no arduino, no connector, no TRS cable
Sorry my bad, you will have this assembly guide: https://www.bilibili.com/video/BV1su4y1E7tG/?spm_id_from=333.337.search-card.all.click
nice ? I'm french, I know english but not chinese... 

You will need to add:
- 52 switch
- 52 hot swap connector
- 52 caps
- 2 arduino pro micro

## Is it worth it ?

We don't have this pcb (I think we can find something near)
If you take an opensource like ergodox
-  5 pcb (like ergodox) on JLPCB is about 20$ (or euros) for 5 keyboard
-  3d printed backplate (200g is about 4euros ?)
-  2 arduino pro (or rp2040) = 7e
-  70 switch = 20 euros
-  70 hot swap connector (if it can be added) = 7euros
-  all the small resistor / capacitor (max 1euros or 2)
-  all the guide and support of the communities

## what did I do

I created this repo to have a small guide (I'm new at creating my own keyboard but I did electronics when I was young)
I reverse engineer the board, so this repo is all that I was able to get

Go to the wiki, I will continue there

## he is pretty but... at what cost...
![do52](https://ae01.alicdn.com/kf/Safdcabb731644e18878e42763c222e19r.jpg_640x640q90.jpg)
