<div id="header" align="center">
   <h1>Always Look On The Bright Side Of Life Player</h1>
   <img src="always.gif"/>
</div>
<div id="header" align="center">
<br>
automatically searches for the song, clicks youtube link, skips ad (using adblocker), maxes youtube and computer volume, and puts video in fullscreen
<br>
<br>

## WARNING: THIS WILL MAX OUT YOUR COMPUTER VOLUME, SO END THE SCRIPT IF YOU DONT WANT IT MAXED OUT
<br>
<br>
NOTE: ONCE IN FULLSCREEN, PRESS "=" TO EXIT CODE AND VIDEO
<br>
<br>
For Colin T
</div>
<br>
<br>

# How To Run
download code into your own repo
<br>
<br>
run commands seperately in project terminal
```
pip install keyboard
pip install selenium
pip install comtypes
pip install pycaw
```

install chrome driver and extract zip into driver folder (whatever version of chrome you have, download that version): https://chromedriver.chromium.org/downloads
<br>
<br>
follow "Method 1: Repack the installed Chrome extension into the CRX file" on https://techpp.com/2022/08/22/how-to-download-and-save-chrome-extension-as-crx/ for this extension https://getadblock.com/en/, and move the crx file to the driver folder
<br>
<br>
run `main.py` and enjoy the music
<br>
<br>
if wait times for "switching tabs and searching" and "waiting for tab to load to click fullscreen button" are too short/long, change them in `main.py` at the top of the code
```
switchTabsAndSearchTime = [YOURTIMEHERE];
waitForTabToLoadForFullscreen = [YOURTIMEHERE];
```

if you want to change how high the youtube and computer volume go, change them in `main.py` at the top of the code
```
MAXVOLUMECOMPUTER = [YOURVOLUMEHERE]; # 0-1
MAXVOLUMEYOUTUBE = [YOURVOLUMEHERE]; # 0-100
```
