###  Simple TikTok Video Downloader 
need
```
sudo apt-get install curl
git clone --depth 1 https://github.com/rouze-d/tiktok-download
```
<br>video title/caption save in @(name)-title.txt<br/>
<br/>
file:<br>
tik.sh - download single video.<br>
tikwm.sh - video No/Remove WaterMark.<br>
tok.sh - download all video. \[make sure load all page. (scroll down until finish).<br>
Browser recommend : Chrome, Opera (Not work with Firefox). In input name, put target ID/username. (see video tok.mp4).\]
-----
### MY MODIFICATIONS:
-this version has been modified to use the curl that Homebrew installs, not the default system curl<br>
-requests are routed through tor to avoid beeing shutdown by tiktok server<br>
-tor ip is reseted at the end of each video to avoid beeing detected
