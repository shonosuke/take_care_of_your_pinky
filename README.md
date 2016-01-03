Take care of your pinky
========
## What is it?
A keymap to avoid ["Emacs Pinky"](https://en.wikipedia.org/wiki/Emacs#Emacs_pinky) problem.

## How to use?
1. Install [Karabiner](https://pqrs.org/osx/karabiner/) (for OSX)

2. Download config file for Karabiner
```
git clone git@github.com:shonosuke/take_care_of_your_pinky.git
mv ~/Library/Application\ Support/Karabiner/private.xml ~/Library/Application\ Support/Karabiner/private.xml.orig
cp take_care_of_your_pinky/private.xml ~/Library/Application\ Support/Karabiner/
```

3. Karabiner -> Change Key -> Reload XML -> Check "Control to Command+Q (only in emacs)"

4. Press the Control key in emacs