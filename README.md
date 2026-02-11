## Config for hyprland (Arch linux)
#### Install required packages
Installing yay  
` sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si `

Installing other packages  
` sudo pacman -S hyprpaper pipewire wireplumber hyprpolkitagent qt5-wayland qt6-wayland noto-fonts cmus cava htop rofi uwsm waypaper dunst fish `

` yay -S --needed aylurs-gtk-shell-git wireplumber libgtop bluez bluez-utils btop networkmanager dart-sass wl-clipboard brightnessctl swww python upower pacman-contrib power-profiles-daemon gvfs gtksourceview3 libsoup3 grimblast-git wf-recorder-git hyprpicker matugen-bin python-gpustat hyprsunset-git `

Installing hyprpanel  
` yay -S ags-hyprpanel-git `
