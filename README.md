# clover-theme-minimal-dark
Dark version of minimal theme with a few tweaks for [the Clover UEFI bootloader](http://sourceforge.net/projects/cloverefiboot), based off [clover-theme-minimal by Alex James](https://github.com/al3xtjames/clover-theme-minimal).

![Screenshot of the theme](https://github.com/ImmersiveX/clover-theme-minimal-dark/blob/master/screenshot.png "Screenshot of the theme")

### Installation
Place the theme folder in /EFI/CLOVER/themes, located on the EFI system partition.
Then, edit your Clover config.plist to select the theme.
``` 
...
<key>Theme</key>
<string>clover-theme-minimal-dark</string>
...
```

By default, **labels** and **badges** for the boot entries are hidden. If you would like to enable them, you can edit the theme.plist file:

```
...
<key>Label</key>
<true/>
...
```
```
<key>Badges</key>
<dict>
    ...
    <key>Show</key>
    <true/>
```
### Credits

- [Evan Purkhiser - original theme](https://github.com/EvanPurkhiser/rEFInd-minimal), which uses [OS icons from SWOriginal](https://www.deviantart.com/sworiginal/art/Lightness-for-burg-181461810). 
- Ukr55 - cursor icon, font image, misc icons
- [Alex James - clover-minimal-theme](https://github.com/al3xtjames/clover-theme-minimal)
- [Icons8](https://icons8.com/)
