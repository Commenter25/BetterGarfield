# Version Changelog
BetterGarfield uses [Semantic Versioning](https://semver.org/), and this changelog is based off [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).  
In a nutshell, here's what that means in a very heavily paraphrased manner:
  * Versions are formatted like (overhaul).(added stuff).(fixes)
  * Timestamps are in the [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) format, which is YYYY-MM-DD
  * Clicking the version name will show what the repository looked like at the time
  * The list is sorted by new (so if v4.2.0 is the latest, then v4.1.9 will be right below it if that's the previous version)

## 2019-06-04 - [Version 1.1.6](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.6)
small patch thingy, still working on v2 to come someday
### Fixed:
  * Centered arrows in carousel buttons
  * Go Games is now hidden
  * News ticker text is now consistently not bold, thanks Garfield GO

## 2019-04-06 - [Version 1.1.5](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.5)
### Changed:
  * It's been about a week now, time to get rid of that little eye catcher for that message below.
(i hate making version increments for these two updates that have almost no value but hey i gotta do it)

## 2019-03-30 - [Version 1.1.4](https://github.com/CommenterOfComments/BetterGarfield/tree/v1.1.4)
Sorry, this is a really disappointing update. I literally just removed something out of date.

BUT, there is something big that I'm working on. I'll still maintain the current version of BetterGarf for now, but I want to focus on this new version. I don't know when it will come out, but you'll love it. If you're one of the people who were impressed by the current BetterGarf, you'll be blown away by BetterGarf v2. That's right. It's happening. And it'll be great. 

I'll release more details when I'm later in development. But if you have any questions, feel free to ask in the issues, or on my Twitter [@Commenter25](https://twitter.com/Commenter25)! One thing I'll say now though, the code shouldn't be nearly as much of a unreadable spaghetti mess, I made that mistake with v1 under the impression that minification would help. It'll help download times for installs/updates, but in reality, it won't do much with a local file. Maybe a small performance difference, but it's not worth making it hard to not only maintain, but for others to contribute to. 

If you notice any bugs with the current userstyle version, let me know, and I'll still release a patch for that. However, I'll likely not be adding anything big to this version. Though, not like there's a whole lot to add when restricted to CSS, huh? :p

I love all of you reading this. You care about the project, and I appreciate that a ton. I'll see you in v2. However long it takes. Let's just hope Paws doesn't screw me over and redesign the website now, huh? But even then, I'll probably end up continuing BetterGarf. I doubt they'll make a perfect Garf site. Wouldn't be surprised if they removed the games just because they don't wanna port them to HTML5. Probably the same reason they removed all the fun animation that the flash based site had. And the downloads. And the e-cards. Damn, I miss the e-cards. Even if they make the perfect site, maybe I'll just turn BetterGarf into "Garfield.com easter egg hunt" for funsies

Alright, done with the long text. Signing off. remember to watch and star the repository and share bettergarf with all your frie-
### Fixed:
  * Removed the fix for "the The Garfield Show" since that line is now removed from the ticker
### Changed:
  * Now a different line says something else, which might've brought you here 😉

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
Initial release of BetterGarfield  
Please let me know if there's anything you want added, or if anything is broken!

## 2019-02-10 and before
idea and develeopement and stuf
