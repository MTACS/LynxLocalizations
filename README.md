# Lynx 2 Localizations
Repository containing all Lynx 2 localizations

For any questions regarding localization, contact me on [Twitter](https://twitter.com/mtac8) or [Discord](https://discordapp.com/users/451747491549806593)

# Adding a translation

Partial translations exist for [Arabic](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/ar.lproj), [German](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/de.lproj), [Turkish](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/tr.lproj), [Spanish](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/es.lproj), [Chinese (Simplified)](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/zh-Hans.lproj) and [French](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/fr.lproj).

If you are updating one of these languages, download the .strings files from the appropriate link above. If you are adding a new language, download each .strings file from the [strings](/strings) template folder. 

Replace the lowercase string with your translation. [Open a new issue](https://github.com/MTACS/LynxLocalizations/issues/new?assignees=MTACS&labels=&projects=&template=language-addition.md&title=%5BTRANSLATION%5D) and attach each translated strings file.


#
_Open .strings files as plain text file if possible. If you are using a Mac, open the files in TextEdit as Xcode may save the file in binary format. Please do not fork and create pull requests for this repository, use issues instead. It is much easier to maintain and keep translations up to date_
#

### Examples

_Keys with no text (ex: ```"KEY" = "  "``` or ```<key>KEY</key><string>  </string>``` ) are keys that need to be translated_

#
***French***

```Settings.strings```

<sub>strings format</sub>   
```"SETTINGS" = "Réglages"```   

<sub>plist format</sub>   
```<key>SETTINGS</key>```   
```<string>Réglages</string>```

#
***Arabic***
```Music.strings```

<sub>strings format</sub>   
```"MUSIC" = "الموسيقى"```

<sub>plist format</sub>   
```<key>MUSIC</key>```   
```<string>الموسيقى</string>```

#
***Chinese (Simplified)***
```SpringBoard.strings```

<sub>strings format</sub>   
```"SPRINGBOARD" = "系统桌面"```

<sub>plist format</sub>   
```<key>SPRINGBOARD</key>```   
```<string>系统桌面</string>```

# Updates

Localizations will distributed as a separate package to help with latency between new features and untranslated strings. Please get all localization updates for Lynx from [here](https://mtac.app/repo)
