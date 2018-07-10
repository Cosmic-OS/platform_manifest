<img src="https://raw.githubusercontent.com/Cosmic-OS/platform_packages_apps_Settings/pulsar-release/res/drawable/cos_about_logo.png"> 

Cosmic-OS
=========

Credits 
-------
 * [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
 * [**AOSCP**](https://github.com/cypheros/)

Getting Started 
--------------- 
To get started with the Cosmic-OS sources, you'll need to get 
familiar with [Git and Repo](http://source.android.com/source/version-control.html). 

Initialize the Repositories 
---------------------------

    repo init -u https://github.com/Cosmic-OS/platform_manifest.git -b pulsar-release
    repo sync --no-tags --no-clone-bundle --force-sync -c

 -j# -Set jobs by just replacing # with what you wish

This will initialize the new repository and begin the initial sync. This can take a while!

Building the System 
-------------------
 Initialize the ROM environment with the envsetup.sh script. By entering command (i).

    . build-cos.sh #device

 Just replace #device with your device name 

 EG 
    . build-cos.sh berkeley

 OR

     . build/envsetup.sh
     lunch cos_<device>-userdebug
     brunch <device>
