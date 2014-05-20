ubuntu_udev_rules_4_android
===========================

ubuntu udev rules for android devices

This is the udev rules needed for Ubuntu Linux to recognize new Android devices.

Originally copied from AOSP source.  As I have many devices, it is more convinient for me to archive this file so I can
just download it and use it immediately with new machines or build-bots

place this file (51-android.rules) under

/etc/udev/rules.d/

to restart udev, simply do this:

sudo service udev restart

