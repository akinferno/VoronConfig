# VoronConfig
Files for my Voron 2.4r2 "Devastator"
----------------------------------

This is just a place for me to store and share components of my config. It may or may not be working at the moment. Use at your own risk!

KIAUH



INSTALL LED EFFECTS
---------------------------------------------
cd ~
git clone https://github.com/julianschill/klipper-led_effect.git
cd klipper-led_effect
./install-led_effect.sh

Moonraker addition for LED effects
------------------------------------------
[update_manager led_effect]
type: git_repo
path: ~/klipper-led_effect
origin: https://github.com/julianschill/klipper-led_effect.git
is_system_service: False


INTERESTING STUFF
--------------------------------------------
Power Loss recovery:
https://github.com/The--Captain/plr-klipper

Eric Zimmerman tools
https://github.com/EricZimmerman/VoronTools
