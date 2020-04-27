# BlackMate
![Alt text](blackmate-kde.png?raw=true "Blackmate on KDE")
![Alt text](blackmate.png?raw=true "Blackmate on XFCE")

## Blackmate

Blackmate is a generator for the tools list of BlackArch Linux OS, originally made for the XFCE4 Desktop. The script fetches the latest tools and generates a new entry on the start menu.
I wanted to have a BlackArch setup running on KDE which was not possible with the original script so I improved it a bit. It can now run on all major Desktops including KDE Plasma.

## still to go
- Fixing Folder Icons
- Fix Typos
- Generally clean up code

## How to

```
git clone https://github.com/byReqz/blackmate
sudo mv blackmate /usr/share/
sudo cd /usr/share/blackmate
sudo sh blackmate.sh
```
License GNU/GPL v3, original code written by Dimitri Mader (dimitri@linux.com)
