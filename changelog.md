# Version Changelog
BetterGarfield uses [Semantic Versioning](https://semver.org/), and this changelog is based off [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).  
In a nutshell, here's what that means in a very heavily paraphrased manner:
  * Versions are formatted like (overhaul).(added stuff).(fixes)
  * Timestamps are in ISO 8601, which is YYYY-MM-DD
  * Clicking the version name will show what the repository looked like at the time
  * The list is sorted by new (so if v4.2.0 is the latest, then v4.1.9 will be right below it)

## 2019-03-01 - [Version 1.1.3](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.3)
### Fixed:
  * Got rid of sharing icons on the comics page (i should really have looked through on a clean browser _before_ release)
  * Added padding to the news page.
  * Hidden the entertainment button no matter what on resolutions between 768px and 992px

## 2019-02-26 - [Version 1.1.2](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.2)
### Changed:
  * The option for hiding the home carousel is now simply a option to hide all carousels

### Fixed:
  * Fixed the clip path for the dark mode logo (cropped some of the bubble before) 
  * Games button appears on most screens (anything above 767px in width)
  * Ratings were accidentally misaligned after voting from trying to add support with the scaling system (which i couldn't figure out anyway)
  * Characters page sucks, reverted to button below 768px
  * Of all the places to advertise the new Garf Solitare/Mahjong, why the fuck on the comics dropdown?
  * Updated namespace (it's now consistent between all of my styles)
  * File is now UTF-8 instead of Unicode, which not only halfed the file size via sorcery, but also GitHub actually shows it because they suck _**BINARY FILE NOT SHOWN BINARY FILE NOT SHOWN**_

## 2019-02-15 - [Version 1.1.1](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.1)
### Fixed:
  * Fixed some night mode bugs (including the comic calendar)
  * Added support for the site's scaling (how did i forget about this)
  * Accidentally had removed the background gradient thingy for the games page
  * Age check had the original project name. Also added a mention to the wiki
  * Fixed the hover effect on the characters page
  * Added a background to the character page boxes
  * Probably some other stuff I forgot to put here

## 2019-02-14 - [Version 1.1.0](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.0)
### Added:
* A dark mode
* Options
  * Toggle hiding the Entertainment button (default on)
  * Toggle hiding the home page carousel (default off)
  * Toggle hiding the footer (default off)
  * Toggle dark mode (default off)
* Semi-nested code (via the Stylus preprocessor [not to be confused with Stylus the extension])
* Email Garfield page has had its tabs removed (they're redundant clutter)
* Additional @author metadata

### Fixed:
  * Listable items pages (games, apps, books, etc) would show the Play/More text when selecting. It'll still copy, but I can't fix that.
  * Actually changed the version number on the style before releasing :p
  * Fixed a typo in the news ticker ("Watch the The Garfield Show on YouTube!")
  * The comic control bar looks normal when searching now (looked cut off before)
  * The hover for listable items was 1 pixel off the gradient thingy. I know, I just saved your life, get off your knees.
  * Whoops! I forgot to add the mouse-over-click feature to the characters page!

## 2019-02-11 - [Version 1.0.0](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.0.0)
Initial release of the style (no shit)  
Please let me know if there's anything you want added, or if anything is broken!

## 2019-02-10 and before
idea and develeopement and stuf
