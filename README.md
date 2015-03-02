# Sublime Text 3 binary patches 

**Please note**: this patches works only for OSX versions of Sublime Text 3.

## Requirements
- `brew`

## How to use
Assuming you already downloaded Sublime Text 3, copied app to your `/Applications` directory and still have downloaded .dmg attached:
```
brew install bsdiff
cd ~/Downloads && git clone https://github.com/yumitsu/sublime-bp.git && cd sublime-bp
bspatch /Volumes/Sublime\ Text/Sublime\ Text.app/Contents/MacOS/Sublime\ Text /Applications/Sublime\ Text.app/Contents/MacOS/Sublime\ Text ./sublime<your version>.patch
```
