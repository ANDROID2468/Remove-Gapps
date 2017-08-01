## Remove Gapps is a project created 2017 by CHEF-KOCH to remove all Google apps (Gapps)

The goal is to switch from Gapps to NanoMod, to remove all Google services (except Coregms.apk and Webview [cause there important]) to get control pack to you!

How does it work?
=================

* Script removes apps from /system partition. Probably some of them was updated and additionally stored in your internal memory.
* The flashable-zip supports Android 2.3+ up to Android Nougat 7.1.2.
* The script can mount /system automatically which means you don't need do it by yourself.
* The script was tested on CyanogenMod (LineageOS) only but theoretically should work on most ROM's. 
* It's flashable via CWM and TWRP. 


What it deletes?
=================
* The Script will delete the default Google Launcher.
* The Script also removes Google Dialer, Google Keyboard, Google Maps, Google Play Store & Google Play Store which means you need to install alternatives before you use this script - or simply install NanoMod.
* It's highly recommended to wipe dalvik/ART-cache to rid out of unused cache files after flashing the package.
* The full list is viewable/editable under 'delete.sh'.


**Please backup or do a full backup via recovery before you install it.** 


Research and alternatives
* https://forum.xda-developers.com/apps/magisk/module-nanomod-5-0-20170405-microg-t3584928
* https://forum.xda-developers.com/android/apps-games/app-microg-gmscore-floss-play-services-t3217616