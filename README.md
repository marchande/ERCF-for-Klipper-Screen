This project was born from a need, the need to control certain functions of the ERCF directly from klipper screen and not having to use a web browswer
This is not entirly my work, as KDE-47 In the ERCF_Questions channel on the voron discord ((https://discord.com/channels/460117602945990666/909743915475816458)) was the one that did most of the inital scripting, I just cleaned things up a bit and created the custom icons 


instructions:

1. Unpack the ERCF_Klipper_Screen.rar 

2. You will need to use a program like winscp or have someway of FTP into your klipper files on your Pi.

3. Goto your klipperscreen/styles/images folder (the one you use i.e in my case z-bolt) on your Pi , then copy the contents of 	the images folder.
4. Copy the contents of the Klipperscreen.conf and add it to th top portion of your current klipperscreen.conf file NOTE: If you are using more than 9 tools , you will need to uncomment out the sections noted. This setup is for 12 cart. If you need more you can create them.
5. I have included ERCFextruder.svg files for up to 15 tool heads.

Restart Klipper , You should then be able to access the ERCF menu by clicking on Actions. When the print is paused you can access the ERCF menu by clicking on the settintgs menu. This is a built in fool safe. Once you have fixed your ERCF problem just hit resume and your print will continue.

ENJOY
