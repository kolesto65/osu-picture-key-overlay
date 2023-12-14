# osu-picture-key-overlay
Simple web overlay with pictures to stream osu!
Changes picture everytime Z or X is pressed.
Supports gif, png, jpg and basically every browser-friendly image format (trasparency work too). Works with OBS or any other streaming software that supports browser sources.
Demonstation: https://youtu.be/Wsv-RTdVyQI

How to use:
1. [Download](https://github.com/kolesto65/osu-picture-key-overlay/releases) and unpack latest zip everywhere you want.
2. Add your prefered pictures to "assets/images" folder.
3. Start opko.exe
4. It will probably won't start because Im'a professional shitcoder, so create an issue on github, I'll try to help you make it work.
5. In case it works, just add it as browser source in OBS, use link provided by app (default: http://localhost:3777)
To change pictures, simply replace them in "images" folder with new ones, then edit your browser source in OBS and click "Refresh cache of current page".
VERY IMPORTANT!!!! Don't launch two executables of OPKO at once, it will make your mouse cursor lag.

And now about settings.json:
1. "KeyA" and "KeyB" are keys you use to play osu (Z and X by default)
2. "ext" is extension of your images (gif by default)
3. "singletap" if you set this to true, then image will be changing no mater what key is pressed out of two (false by default)
4. "port" is just a port that will be used by web server

P.S. Source code is not provided here since I'm ashamed of my coding skills, but VirusTotal should not ring the alarm.
