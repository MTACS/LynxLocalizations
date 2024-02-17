# Lynx 2 Localizations
Repository containing all Lynx 2 localizations

Download on [mtac.app](https://mtac.app/repo)

For any questions regarding localization, contact me on [Twitter](https://twitter.com/mtac8) or [Discord](https://discordapp.com/users/451747491549806593)

## New Strings

Here is a list of new strings added by version. Use these to update translations to the latest version of Lynx

<details>
  <summary><h3><strong>2.4.8</strong><h3></summary>
  
  ### CarPlay.strings

    "CUSTOM_ICON_LAYOUT_COLUMNS" = "Custom Columns";
    "CUSTOM_ICON_LAYOUT_ROWS" = "Custom Rows";
    "CUSTOM_ICON_LAYOUT_SUBTITLE" = "Change icon layout";
    "CUSTOM_ICON_LAYOUT_SUBTITLE_COLUMNS" = "Set number of icon columns";
    "CUSTOM_ICON_LAYOUT_SUBTITLE_ROWS" = "Set number of icon columns";
    "CUSTOM_ICON_SIZE" = "Custom Icon Size";
    "CUSTOM_ICON_SIZE_SUBTITLE" = "Set size of displayed icons";
    "HIDE_BLUR_VIEW" = "Hide Blur View";
    "HIDE_BLUR_VIEW_SUBTITLE" = "Remove blur from Status Bar";

  ### Lockscreen.strings

    "HIDE_LEGAL_TEXT" = "Hide Legal Text";
    "HIDE_LEGAL_TEXT_SUBTITLE" = "Remove legal text from Lockscreen";

  ### Settings.strings

    "HIDE_VPN_SUBTITLE" = "Remove VPN cell from main Settings page. Can still be accessed via General -> VPN & Device Management";
    "WALLPAPER_BLUR_STYLE" = "Blur Style";
    "WALLPAPER_BLUR_STYLE_SUBTITLE" = "Choose wallpaper overlay blur style";

  ### SpringBoard.strings

    "HIDE_HANDOFF_SUBTITLE" = "Remove handoff suggestions from suggested section";
    "SHARE_SHEET" = "Share Sheet";
    "HIDE_SHARE_CONTACTS" = "Hide Contacts Row";
    "HIDE_SHARE_CONTACTS_SUBTITLE" = "Remove contacts from share sheet";
    "HIDE_SHARE_APPS" = "Hide Apps Row";
    "HIDE_SHARE_APPS_SUBTITLE" = "Remove app suggestions from share sheet";
    "USE_CUSTOM_HOMEBAR_COLOR" = "Custom Homebar Color";
    "USE_CUSTOM_HOMEBAR_COLOR_SUBTITLE" = "Swipe left to set color";
    "HIDE_HOMEBAR_GLOBALLY" = "Hide Everywhere";
    "HIDE_HOMEBAR_GLOBALLY_SUBTITLE" = "Remove Home Bar from all views";

  ### StatusBar.strings

    "HIDE_NOTCH_SUBTITLE" = "Add view to hide notch/dynamic island";
    "DISABLE_ISLAND_OUTLINE" = "Disable Outline";
    "DISABLE_ISLAND_OUTLINE_SUBTITLE" = "Remove line from edge of dynamic island";
    "DYNAMIC_ISLAND" = "Dynamic Island";

  ### Translations.strings

    "CHINESE" = "Chinese";
    "VIETNAMESE" = "Vietnamese";
    
</details>

# Adding a translation

Partial translations exist for [Arabic](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/ar.lproj), [German](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/de.lproj), [Turkish](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/tr.lproj), [Spanish](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/es.lproj), [Chinese (Simplified)](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/zh-Hans.lproj) and [French](https://github.com/MTACS/LynxLocalizations/tree/main/com.mtac.lynxtwo.localizations/layout/Library/PreferenceBundles/lynxprefs.bundle/fr.lproj).

If you are updating one of these languages, download the .strings files from the appropriate link above. If you are adding a new language, download each .strings file from the [strings](/strings) template folder. 

Replace the lowercase string with your translation. [Open a new issue](https://github.com/MTACS/LynxLocalizations/issues/new?assignees=MTACS&labels=&projects=&template=language-addition.md&title=%5BTRANSLATION%5D) and attach each translated strings file.


#
_Open .strings files as plain text file if possible. If you are using a Mac, open the files in TextEdit as Xcode may save the file in binary format._
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
