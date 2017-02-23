# Linux-Spotify-Current-Song-for-OBS
This simple bash-script allows you to get the current spotify-song playing and put it into OBS.

## Installation
### Requirements
For this to work, you have to have ```wmctrl``` installed. This is needed to find the window title of Spotify. 
You can install wmctrl by using the command ```sudo apt-get install wmctrl``` 

### Installing
Download the script and give it the appropriate rights to run (you don't need sudo or anything like that).

```
git clone https://github.com/flymia/Linux-Spotify-Current-Song-for-OBS.git

chmod +x spotifycurrentsong.sh

./spotifycurrentsong.sh
```
