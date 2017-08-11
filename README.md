# Discord-Music-Status
## A Program to display your currently played Music as your Discord Status

The status won't display on your own client for some reason, Discord's fault, however if you look on another client or mobile you see it will be displayed.

##### The program will work with:
- Spotify
- iTunes
- Winamp
- foobar2000
- VLC
- Google Play Music Desktop Player
- Quod Libet

##### Requirements:
- Python 3.6
- Discord.py and Logbook installed via pip
- Snip / https://github.com/dlrudie/Snip/releases/latest

##### Install:
1. Install Snip and run at least once, to generate snip.txt
2. Find your Discord Login token (See "Finding Login Token below")
3. Update defaultconfig.ini with your token and path to snip.txt, your path to snip.txt should look something like this. `C:\Users\User\Documents\Snip\snip.txt`
4. Rename defaultconfig.ini to config.ini **IMPORTANT**
5. Run `run.py`

##### Finding Login Token
1. Open Discord
2. Press Ctrl+Shift+i
3. Click "Application" tab
4. Expand Storage > Local Storage > https://discordapp.com/
5. Find "token" under "key"
6. Copy the text in quotes on the same row, DO NOT KEEP THE QUOTES

##### Logging out
To log out, send "m.quit" anywhere on Discord
