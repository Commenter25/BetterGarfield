# Contributing Guide
Thank you for your support!  
This guide will tell you the best way to help.

## Requirements
* Basic understanding of CSS
* Maybe a more advanced understanding, all depends
* A basic understanding of how to use GitHub
* Everyone's best interest in mind
* Willing to only use English <sup>sorry, it's just easier this way :(<sup/>
  
## Steps to making a good contribution
1. Download BetterGarfield (duh)
   - Optional steps:
     - Copy the code and import it to the non-UserCSS editor
     - Beautify the code to your preference (but be sure you don't copy that code into your pull request later!)
2. Find the code section that fits best
   - Example: If you're changing the header, go to the global block (domain("garfield.com")) and the section for the header
3. Make the changes you want to make
4. Please _test it before doing anything else!_
5. Minify the code (instructions further down)
6. Fork the repository
7. Replace the BetterGarfield**_-Dev_** file with yours (This is your own copy, don't worry)
8. Make sure everything you didn't change is up to date (so you don't accidentally revert anything)
9. Go back to the normal repo, and submit a pull request!

## Minifying your code
Now, if you don't know what minification is, it's basically making the code as small as possible.  
We do this because, while it makes the code harder to read, it reduces the file size, and makes it faster.

Take a look at this example.
```
.watchbensononyoutube {
  color: #983232;
  padding-top: 2px;
  padding-left: 43px;
  padding-right: 43px;
  padding-bottom: 2px;
}
```
If you didn't understand that reference, that's good.  
The point is, we can simplify this code. The first step is to use shorthand properties.  
You see how there's four different padding entries? We can simplify this to simply one.
```
.watchbensononyoutube {
  color: #983232;
  padding: 2px 43px;
}
```
That alone chopped ~66 characters. It went from 130 to 64.  
Once you've optimized the code itself, you can remove most of the spaces.
```
.watchbensononyoutube{color:#983232;padding:2px 43px}
```
From 64 to 53. 11 characters removed, same functional code.  
That doesn't _sound_ like a lot, but trust me, that adds up.

Most likely, you're going to have multiple lines of code.  
Despite minifying, I would prefer if you still put a new line between each thing.
For example, instead of doing this:
```
.watchbensononyoutube{color:#983232;padding:2px 43px}.uwrtz{color:#00ff00}
```
Do this:
```
.watchbensononyoutube{color:#983232;padding:2px 43px}
.uwrtz{color:#00ff00}
```
In my opinion, this significantly increases the readiblity without too much of a file size bloat. I would significantly prefer that you do it this way.

## Rules
Don't try and change stuff to `html:{display:none}`  
That's a bit of a simplification, but basically, don't be a jerk and/or intentionally try to fuck stuff up. I _will_ review your code and make sure it functions properly. So don't try it.  
Otherwise, if you're someone who has good intentions, don't worry about anything.
