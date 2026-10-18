![RSDK Decompilation for Windows XP](https://i.imgur.com/ST9H2xz.png)
## RSDK Decompilation Port for Windows XP

all three versions of the rsdk decompilation, fully compiled, optimized, and ported to run natively on windows xp

mods have been tested and are working on all three versions

includes precompiled executable files for the following alongside the necessary dll files needed to run them:
- [RSDKv3 (Sonic CD)](https://github.com/RSDKModding/RSDKv3-Decompilation)
- [RSDKv4 (Sonic 1/2)](https://github.com/RSDKModding/RSDKv4-Decompilation)
- [RSDKv5[U] (Sonic Mania)](https://github.com/RSDKModding/RSDKv5-Decompilation)

everything was tested on _real windows xp hardware_ (dell inspiron 9100, 2.8ghz pentium 4, 1gb ram) inside a service pack 2 install

for obvious reasons, **no data.rsdk files are included; you must provide your own** (sonic cd for rsdkv3, sonic 1 and/or 2 for rsdkv4, and sonic mania for rsdkv5, though that game's decompilation dll is included)
this pack contains ONLY the executables and their respective dll files

## FAQ:

**Q:** is this project vibecoded?

**A:** i'm definitely gonna have a lot of people suspicious about this, especially since this project came about amidst the recent influx of vibecoded (and often HORRENDOUSLY "optimized") pc ports/recomps that have been multiplying like f'n rabbits, but **no, there was no ai involved in this at all**;
all i did was simply run the pre-existing rsdk decompilation source repositories through w64devkit with the proper optimizations for xp, adapting the optimizations for each version as i went
