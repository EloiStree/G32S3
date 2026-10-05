```
git clone --recursive https://github.com/EloiStree/G32S2.git
cd G32S3
git submodule foreach "git switch main"
```
# G32S3

> Simple app to display your ESP32-S3 camera feed in a Godot app on the Steam Frame and other devices.

When I am teaching from the Steam Frame using video, I need a small, portable camera to carry with me so I can show things.   
I know the camera is shit, but it's portable and easy to connect.  
So let's at least make a little app you can install on your Frame and Android phone.  

Info:  https://github.com/EloiStree/HelloXiaoCamToRXTX


**Reminder for development of the app:**
I could make a big app around it, but I need to stay focused on keeping it simple so it can be published on Flatpak one day.
The aim for me is to make it publishable on any platform for teaching.
