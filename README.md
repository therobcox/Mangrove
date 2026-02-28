# Mangrove
Dynamic Background for gnome desktop

![Mangrove3](https://github.com/user-attachments/assets/5ab215c3-5bc4-4808-a9e7-ad0f12642cd3)

Mangrove

# Description
A simple Dynamic Background theme for gnome desktop.

The brightness syncs with the time of day creating a subtle and pleasant background.

The Dynamic Background can be installed directly into the system backgrounds folder.

Then you can enable using the gnome Settings -> Backgrounds section of your distribution. 

![Mangrove1](https://github.com/user-attachments/assets/532ac8fe-bf9a-47fa-8865-911eb9ece1f5)

Mangrove

# Installation
Download Mangrove Dynamic Background here: <a href="https://www.gnome-look.org/p/2313312/">https://www.gnome-look.org/p/2313312/</a>

To install, copy files to the system backgrounds folder using root privileges.

 - Extract Mangrove.tar.xz to Downloads folder
 
 - Right-click Mangrove folder and select "open in terminal"
 
 
Copy theme folders to backgrounds and change permissions to root
 
 - sudo cp -r mangrove /usr/share/backgrounds/
 
 - sudo chown -R root:root mangrove
 
 - sudo chmod -R 755 mangrove
 
 
Copy mangrove-wallpapers.xml to gnome-background-properties and change permissions

 - sudo cp mangrove-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root mangrove-wallpapers.xml
 
 - sudo chmod -R 755 mangrove-wallpapers.xml 

 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."


# Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in


# Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/mangrove
 
 - sudo rm -r /usr/share/gnome-background-properties/mangrove-backgrounds.xml


# Extras

Looks great with WaterCoolerXT Theme:

WaterCoolerXT Theme here: <a href="https://github.com/therobcox/WaterCoolerXT">https://github.com/therobcox/WaterCoolerXT</a>

WaterCooler Icon Theme here: <a href="https://github.com/therobcox/WaterCoolerXT-Icons">https://github.com/therobcox/WaterCoolerXT-Icons</a>

