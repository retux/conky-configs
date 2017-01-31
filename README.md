# conky-configs
conky configurations and customizations
This is a fistful of configurations for conky. Share your one too!

This is a vertical running config for conky. For 'icons' it uses a set of fonts:

Open Logos: www.dafont.com/es/openlogos.fonttotal 
Pizza Dude Bullets: http://www.dafont.com/es/pizzadude-bullets.font
Style Bats: http://www.dafont.com/es/style-bats.font

Thanks to those fonts guys.

1)  ttf file can be locates in /usr/local/share/fonts 

$ ls -l /usr/local/share/fonts/
-rw-r--r-- 1 root staff 80584 ene 29 20:17 openlogos.ttf
-rw-r--r-- 1 root staff 28324 ene 29 20:22 PIZZADUDEBULLETS.ttf
-rw-r--r-- 1 root staff 21296 ene 29 20:22 STYLBCC_.TTF


2) Update the font cache by running:

 # fc-cache -fv

3) Install packages, for instance in Debian:

 # aptitude install conky conky-all

4) Copy configuration file to your home directory 

 $ cp conky-vertical-with-icons.rc ~/.conkyrc

5) Start conky, by cli and then auto start if you want.

 

