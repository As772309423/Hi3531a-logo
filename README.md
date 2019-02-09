# Hi3531a-logo
Heise's loading is mainly realized by inputting relevant commands after uboot starts (before kernel starts). Specific commands to be used and the order of commands can be referred to Heise's development document HiMPP Boot Screen Use Guide.


Heis logo only needs to modify two files in the U boot section. For Hi3531a,
1）/HisiSDK/Hi3531A_SDK_V1.0.5.0/osdrv/opensource/u boot/u-boot.-2010.06/include/configs/hi3531a.h.  
2) /HisiSDK/Hi3531A_SDK_V1.0.5.0/osdrv/opensource/u boot/u-boot-2010.06/common/env_common.c.

The modified code of these two files is already in the project. You just need to replace the two files in the same path and modify the corresponding parameters (such as the address of the image loaded in memory, the address of the data read from Flash, the size of the picture, etc.) to load Heise logo.
