# open_core_macos_monterey

https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html

1. download macOS installer dmg?
   sudo python installinstallmacos.py
2. USB format and make it as bootting 
    sudo /Application/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/USB_Mac
3. setting EFI https://github.com/corpnewt/MountEFI
   MountEFI.command
   
   mount EFI
   
4. copy these EFI folder to EFI


5. The End!!!
