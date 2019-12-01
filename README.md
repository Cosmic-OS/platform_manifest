<img src="https://raw.githubusercontent.com/Cosmic-OS/platform_manifest/quasar-release/Cosmic-OS%20Header.png"> 

Cosmic-OS
=========

Credits 
-------
 * [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)

Getting Started 
--------------- 
To get started with the Cosmic-OS sources, you'll need to get 
familiar with [Git and Repo](https://source.android.com/setup/develop.html). 

Branch Info
-----------
* quasar-release - Android 10
* corona-release - Android Pie
* pulsar-release - Android Oreo

Initialize the Repositories 
---------------------------

    repo init -u https://github.com/Cosmic-OS/platform_manifest.git -b quasar-release
    repo sync --no-tags --no-clone-bundle --force-sync -c -j#

 -j# -Set jobs by just replacing # with what you wish

This will initialize the new repository and begin the initial sync. This can take a while!

Building the System 
-------------------
 Initialize the ROM environment with the envsetup.sh script. By entering command (i).

     . build/envsetup.sh
     lunch cos_<device>-userdebug
     brunch <device>
