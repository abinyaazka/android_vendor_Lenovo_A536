Lenovo A536
==============

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.3GHz Quad-Core MT6582
GPU     | Mali-400MP2
Memory  | 1GB RAM
Storage | 8GB
Battery | 2000 mAh
Display | 5.0" 854 x 480 px
Camera  | 5MPx, LED Flash


LineageOS build

* Device tree

        # https://github.com/abinyaazka/android_device_lenovo_a536

* Init

        # repo init -u git://github.com/LineageOS/android.git -b cm-13.0
        
        # repo sync -f --force-sync --no-clone-bundle
        
* Build

        # source build/envsetup.sh
        
        # brunch cm_a536-userdebug

* Credits

        # darklord4822        
        # SRT @https://vk.com/smart_rom       
        # sprout team        
        # abinyaazka        

