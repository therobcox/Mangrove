Mangrove Dynamic Wallpapers by robcox
________________________________________

To install, copy files to the system backgrounds folder using root privileges

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


Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in
 
 
Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/mangrove
 
 - sudo rm -r /usr/share/gnome-background-properties/mangrove-backgrounds.xml
 
 Enjoy!!
 
