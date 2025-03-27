## MrKraken's One Page Guide Translations
This repository is dedicated to my one-page guides. I make them in illustrator and from 2025-03-20 am setting them up in a way for people to contribute translations.
You can find the rendered versions on my [Community Hub profile](https://robertsspaceindustries.com/community-hub/user/MrKraken)
The final versions will all be posted alongside my main image with credit to the translators

## Where is the folder for ______?
Early in the PTU cycle I mark the first version of a guide and then iterate throughout the cycle. When I think there won't be many changes (normally when the patches become release candidates), I'll add the guide folder and begin accepting translations.
*Older guides like my original XenoThreat & Supply or Die are not setup for translations*

## How to use
in the \GUIDENAME\ folders there is a variables.xml file
- Fork this repository
- Find `<v:sampleDataset dataSetName="en_GB"></v:sampleDataset>` & copy it
- Paste after `</v:sampleDataset>`, before `</v:sampleDataSets>`
- *Do not replace or remove any existing datasets*
- Change the new dataSetName to your region locale (eg fr_FR for french)
- When translation is complete, put in a pull request


## Why No Googlesheet?
I was originally going to set this up as a googlesheet and distribute the link to people who wanted to add translations, but the Adobe variables files are not easily parsed to grab all the variable names. It would have taken me far too long to make a parser for the files so github it is!


## Translators
- [Hathor Laser](https://robertsspaceindustries.com/community-hub/post/hathor-laser-one-page-guide-V4mCVfAgVSXbc)
  - [x] 🇫🇷 by [kiouv](https://x.com/Journalduverse)
  - [x] 🇨🇳 by cfdxkk / 星际公民中文百科
  - [x] 🇭🇺 by Karajtek
