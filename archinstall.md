# Installing ArchLinux

## Preconceptions
- arch is hard
    - no, arch requires reading
- arch will always break
    - no, arch is as stable as you make it
- I reinstalled arch 3 times in the last month
    - you're the sysadmin of your system. you'll get better.
- Steps to do anything in arch:
    - what do you want to do?
        - how would a nerd do it?
    - read the wiki
    - READ THE WIKI
    - devise a plan for what you want to do based on its contents
        DON'T BLINDLY PASTE WIKI COMMANDS
- how to use the wiki
    - the wiki is a tree
    - if you don't traverse the tree, you won't find what you want

## Preparation
- examining hardware
- choosing a disk layout
    - ext/xfs
    - "bUt wHaT aBoUt ZFS!?!
    - what about zfs' baby brother
- choosing a boot toolchain
- choosing an environment
    - FULL DE's
        - gnome
        - kde
        - cinnamon
    - BYO DE's
        - xfce
        - lxqt
    - TWM's
        - i3
        - sway
        - hyprland
- Security considerations
    - secure boot
    - encryption
    - boot toolchain considerations

## Installation
- networking
- obtain/create installation media
- time, date, locale, keeb, etc
- setup disks
    - DON'T LISTEN TO THE PARTITIONING SCHEME
- mount whatever bizare disk setup you're created
- package installation
    - choose kernel
    - are headers/dkms required
    - out of tree packages
    - editor (vim, nano, nvim, micro, eMaCs)
    - DON'T FORGET NETWORKING (probably NetworkManager)
- genfstab
- boot toolchain

## Post-Installation
- what we have
    - kernel
    - coreutils
    - init system
    - userspace
    - that's it
- what we don't
    - users
        - sudo
    - applications
    - Desktop Environment
    - AUR
- what now?
- make a user
    - install sudo
    - add user to sudoers somehow
    - other required groups
- DE
    - graphics drivers
    - base DE package
    - audio
    - gui apps
- Security

## Ricing
- the term
- Hyprland
- themes
 
