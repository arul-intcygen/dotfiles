# Instalasi font

> sudo pacman -S ttf-jetbrains-mono
> sudo pacman -S ttf-jetbrains-mono-nerd
> fc-cache -fc

# Instalasi tema
> sudo pacman -S nwg-look (setup theme)
> visit gnome look atau pling (e.g https://www.pling.com/p/1996672/ for catppuccin theme)
> download theme
> setup 

# Instalasi thunar
> sudo pacman -S gvfs thunar-volman tumbler thunar-archive-plugin file-roller
> sudo pacman -S gvfs-mtp gvfs-gphoto2 libmtp (komunikasi dengan android)

# Cek keyboard mapping (untuk keperluan keybinding)
> sudo pacman -S wev
> wev


# install xdg-desktop-portal
> sudo pacman -S xdg-desktop-portal xdg-desktop-portal-hyprland xdg-desktop-portal

# audio volume pake wpctl
> sudo pacman -S pipewire pipewire-pulse wireplumber

# copas dari nvim -> global
> sudo pacman -S grim
> sudo pacman -S wl-clipboard
> sudo pacman -S slurp
> grimblast (from AUR)
> open .config/nvim/init.lua 
> tambah : vim.opt.clipboard = "unnamedplus"
