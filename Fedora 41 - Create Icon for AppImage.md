# Creating a Desktop Icon for AppImage
### Tested in Fedora 41
### Likely Platform agnostic

1. Create folder in ~/ for Appimage.
-- Example: ~/Applications
```bash
$ mkdir ~/Applications
```

2. Place AppImage in the directory

```
$ mv -i Appimage ~/Applications
```

3. Go to /home/username/.local/share/applications/ and create a appimage.desktop file and edit it.

```bash
sudo touch <appimagedesktop>
sudo nano <appimage.desktop>
```

4. Enter the following information in the file. If you do not use sudo in the edit icon doesn't tend to take.

```bash
[Desktop Entry]  
Type=Application  
Name=Joplin-3.1.24.AppImage  
Icon=/usr/share/icons/ePapirus-Dark/64x64/apps/appimagekit-joplin.svg  
Exec=/home/username/Applications/Joplin-3.1.24.AppImage  
Terminal=false  
Hidden=false  
Categories=Utility
```

5. Save and exit the file and the AppImage should show up in your Gnome or KDE menu. Adding additional categories can control where it appears in submenus. 
