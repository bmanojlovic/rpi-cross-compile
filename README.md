Script `debootstrap_raspbian_chroot` is initialy created on 64bit openSUSE system and on it should
work without any issues

Required packages for openSUSE:
    
    zypper in debootstrap qemu-linux-user wget git

Required packages for debian based distros (not tested totally yet, do not use it on debian yet):

    sudo apt-get install debootstrap qemu-user qemu-user-static wget git

In case you are using 64bit environment (prefered) you must install next packages
    sudo apt-get install libc6-i386 lib32stdc++6

