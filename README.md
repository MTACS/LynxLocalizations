# LynxLocalizations
Repository containing all Lynx 1 &amp; 2 localizations

# Adding your language

Fork this repository, and make a copy of the ```en.lproj``` folder located in at the root of this repository. Rename this copy to the corresponding language code, for example (French = fr.lproj). DO NOT change the original ```en.lproj``` folder, make a copy! A list of language codes can be found [here](https://www.ibabbleon.com/iOS-Language-Codes-ISO-639.html). For each ```.strings``` file, CHANGE ONLY THE LOWERCASE STRING! An example being this translated French string: ```"SETTINGS" = "Settings";``` becoming ```"SETTINGS" = "Réglages";``` To finish, create a pull request, and updated strings will be added. Please [contact me](https://twitter.com/MTAC8) with any localization questions. 

# Updating strings

Please use the following guide to find the changed strings and update the appropriate language .strings file accordingly using a pull request.

![Localization](https://mtac.app/assets/images/localization.gif)

# Updates

Localizations will distributed as a separate package to help with latency between new features and untranslated strings. Please get all localization updates for Lynx from [here](https://mtac.app/repo)
