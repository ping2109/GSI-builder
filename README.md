# GSI Builder
### Requirements:
- Use ROM.zip
- ROM must have treble support
- Don't try OneUI
- Download link must be direct

### Tutorials:
1. Fork this repo
2. Go to workflows folder and edit builder.yml
3. Add your ROM's direct link
4. Star the repo and wait at the Actions tab
5. Download link will be available at the Uploading part

- Note: To rebuild a new GSI, change the link and just unstar/star again

### A bit of explaination
- ROM_LINK: your ROM's direct link
- ROM_TYPE: your specified ROM type, which follows:
```
1. Android 9: ColorOS, CubotOS, Flyme, Funtouch, JoyUI, MIUI, Moto, Nubia, OneUI, OxygenOS, Pixel, RazerUI, RogUI, VOS, Xperia, ZUI, ZenUI
2. Android 10: ColorOS, Flyme, JoyUI, LGUX, MIUI, Moto, OriginOS, OxygenOS, Pixel, RogUI, VOS, ZUI, ZenUI
3. Android 11: Pixel, VOS
4. Android 12 S: Pixel
```
- If ROM is not specified in the list above then leave it Generic, DO NOT ENTER SOME BULLSHITS LIKE "Generic DotOS 5.1", LEAVE IT "Generic"! </br>

- BUILD_AB: set to true to build AB GSI
- BUILD_AONLY: set to true to build A only GSI
- ROM_AB: file's name, set to whatever you want but keep the .7z
- ROM_AONLY:file's name, set to whatever you want but keep the .7z

## Example env codes:
1. Build AB GSI
```
ROM_LINK: https://rr.noordstar.me/69b5c654   #direct link
ROM_TYPE: VOS   #ima pretend that this is a VOS rom
BUILD_AB: true
BUILD_AONLY: false   #not building A only
ROM_AB: RickRollOS_AOSP_AB_BLABLABLA.7z
ROM_AONLY: A.7z
```
2. Build A only GSI
```
ROM_LINK: https://rr.noordstar.me/69b5c654   #direct link
ROM_TYPE: Pixel   #ima pretend that this is a Pixel rom
BUILD_AB: false   #not building AB
BUILD_AONLY: true
ROM_AB: AB.7z
ROM_AONLY: RickRollOS_AOSP_Aonly_BLABLABLA.7z
```
3. Build both AB and A only GSI
```
ROM_LINK: https://rr.noordstar.me/69b5c654   #direct link
ROM_TYPE: Generic   #ima pretend that this is a Nusantara or other AOSP rom
BUILD_AB: true   #building both
BUILD_AONLY: true   #building both
ROM_AB: RickRollOS_AOSP_AB_BLABLABLA.7z
ROM_AONLY: RickRollOS_AOSP_Aonly_BLABLABLA.7z
```

# Support:
- Telegram Group: t.me/ping2109market
- Telegram Channel: t.me/ping2109rom
