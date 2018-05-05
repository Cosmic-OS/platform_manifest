<img src="https://github.com/Cosmic-OS/platform_manifest/raw/oreo-mr1/cosmic-os-logo.png"> 

Cosmic-OS
=========

Credits 
-------
 * [**Nitrogen Project**](https://github.com/nitrogen-project)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSCP**](https://github.com/CypherOS)
 * [**OmniROM**](https://github.com/Omnirom)
 * [**ABC ROM**](https://github.com/ezio84)
 * [**Dirty Unicorns**](https://github.com/dirtyunicorns)

Getting Started 
--------------- 
To get started with the Cosmic-OS sources, you'll need to get 
familiar with [Git and Repo](http://source.android.com/source/version-control.html). 

Initialize the Repositories 
---------------------------

    repo init -u https://github.com/Cosmic-OS/platform_manifest.git -b oreo-mr1
    repo sync --no-tags --no-clone-bundle --force-sync -c

 -j# -Set jobs by just replacing # with what you wish

This will initialize the new repository and begin the initial sync. This can take a while!

Building the System 
-------------------
 Initialize the ROM environment with the envsetup.sh script. By entering command (i).

    . build-cos.sh #device

 Just replace #device with your device name 

 EG 
    . build-cos.sh angler 

 OR

     . build/envsetup.sh
     lunch cos_<device>-userdebug
     brunch <device>
