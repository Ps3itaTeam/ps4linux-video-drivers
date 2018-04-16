# ps4-video-drivers
Video drivers required to use 3d acceleration on archlinux.

Original patches from failoverflow: https://github.com/fail0verflow/ps4-radeon-patches


INSTALLATION

1) Update Archlinux:
sudo pacman -Syu

2) Clone the repository

git clone https://github.com/Ps3itaTeam/ps4linux-video-drivers

3) Enter in the pkg folder

cd ps4linux-video-drivers/pkg

4) Install the pkgs

sudo pacman -U *

5) Rename libglx

cd /usr/lib/xorg/modules/extensions
sudo mv libglx.xorg libglx.so

6) Reboot the ps4

sudo reboot
