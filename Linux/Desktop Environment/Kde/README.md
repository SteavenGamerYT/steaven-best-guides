# Steaven Best Scripts
Best Guide for Linux and Windows


# Kde


# Ubuntu 18.04 Lts (or Above) and also Beasd Distros


with blot 


sudo apt update && sudo apt install kubuntu-desktop sddm


without blot


sudo apt update && sudo apt install --no-install-recommends kubuntu-desktop && sudo apt install sddm


sudo systemctl enable sddm.service


sudo systemctl enable NetworkManager.service


# Arch or Manjaro


sudo pacman -Sy xorg plasma plasma-wayland-session kde-applications 


sudo systemctl enable sddm.service


sudo systemctl enable NetworkManager.service


# Fedora


sudo dnf -y group install "KDE Plasma Workspaces"