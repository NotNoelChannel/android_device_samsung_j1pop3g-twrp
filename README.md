Build TWRP From Minimal Omini Sources ( 5.1.1 )

For latest version only clone :

git clone https://github.com/omnirom/android_bootable_recovery.git bootable/recovery --depth=1

$ . build/envsetup.sh

$ lunch

$ make clean && make -j4 recoveryimage

or

$ make -j16 recoveryimage


Contributers :
- Surendrajat
- yshalsager
- Shaon
- HWDEV
