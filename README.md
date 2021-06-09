# ubuntu-gnome-40-2.04
Upgrade Ubuntu 21.04 to Ubuntu 21.04 with only gnome 40 (removing ubuntu-session)

To know more, see README.MD from forced-hirsute repo.

This script forces the update to Ubuntu 21.04, install gnome 40 from the ppa (credits for shemgp) and remove Ubuntu Desktop (ubuntu-session).

Only use Gnome 40 on Xorg.

If something isn't ok with Gnome 40, you can also go to recovery mode, enable networking and go to the root shell:

sudo apt update

sudo apt upgrade -y

sudo apt install ubuntu-desktop -y

sudo apt install ubuntu-session -y
