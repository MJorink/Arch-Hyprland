JaKooLit's script edited for my dotfiles:

https://github.com/MJorink/hypr-dotfiles

Credits:

https://github.com/JaKooLit/Arch-Hyprland


------------------------------------------------------------

Dependencies:
- MAKE SURE YOU HAVE THESE INSTALLED, OR CERTAIN PARTS WILL FAIL
- archinstall minimum (or similar)
- git
- git-lfs

Steps:

    git clone --depth=1 https://github.com/MJorink/Arch-Hyprland.git ~/Arch-Hyprland
    cd ~/Arch-Hyprland
    chmod +x install.sh
    ./install.sh

------------------------------------------------------------

------------------------------------------------------------
Manual Installation:

Dependencies:

- MAKE SURE YOU HAVE THESE INSTALLED, OR CERTAIN PARTS WILL FAIL
- Hyprland
- git
- git-lfs
- (Note that you need a bunch of packages to get the intended experience for these dotfiles, scripted install is recommended) 

If you came here after using a JaKooLit script, continue here:

If you have everything ready to go, follow these steps:

    cd $HOME
    git clone https://github.com/MJorink/hypr-dotfiles
    cd hypr-dotfiles
    cp -r .config $HOME/
    cp -r .themes $HOME/
    cp -r .icons $HOME/
    reboot
    
    
------------------------------------------------------------
