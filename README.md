android_hardware_qcom
=====================

Hardware Repo for jellybean 4.22 for 7x30 devices specifically

upto date as of commit date.

using this repo in cm10.1, pac-man, evervolv, any jb-4.22 android repo

using this folder will require fixing up a line or two in framework folder
specifically hwc blit in ui overlay somewhere in framework

cyanogenmod broke support for our device, no support for display-legacy means having to use this repo instead
so this supports display-legacy, audio-caf works fine since recent changes from arco
