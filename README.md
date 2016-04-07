1) copy to [omnirom tree]/device/explay/HDQuad

2) put prebuilt kernel to /device/explay/HDQuad/prebuilt dir

3) to build use commands:

```
. build/envsetup.sh

lunch full_HDQuad-userdebug

make -j4 recoveryimage V=s
```
