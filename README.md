Script `debootstrap_raspbian_chroot` is initialy created on openSUSE system and on it should
work without any issues

Required packages for openSUSE:
    
    zypper in debootstrap qemu-linux-user wget git

Required packages for debian based distros (not tested totally yet, do not use it on debian yet):

    sudo apt-get install debootstrap qemu-user qemu-user-static wget git

