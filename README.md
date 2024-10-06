# WLED-BLING
Platformio configuration for compiling MoonModules WLED for UM-BLING Board  http://unexpectedmaker.com/bling

Use with the MoonModules version of WLED https://github.com/MoonModules/WLED

You can compile for BLING after installing all the WLED prequisites in PlatformIO by changing the target to `esp32s3_BLING_8MB_PSRAM_qspi`

This override contains all the proper pin numbers to configure the UM-BLING out-of-the-box to work with WLED including the LEDs and the microphone.  

After compiling and flashing the BLING board there are some post setup things you still have to do:

* Set your wifi network 
* Set the 2D layout to 40x8 (I mean, if you want to, you don't have to unless you want to use BLING as a 2D matrix)
* Enable the I2S microphone in Audioreactive settings. 
* have fun with your BLING
