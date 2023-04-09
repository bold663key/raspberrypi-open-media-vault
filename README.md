# RPI-OpenMediaVault
Install OMV on Raspberry Pi


1. Install Raspberry Pi OS Lite 32 bit on your Raspberry Pi

2. Connect ssh to your rpi
If warning is:   REMOTE HOST IDENTIFICATION HAS CHANGED  
You should type commend to your local computer terminal: sudo rm .ssh/known_hosts 
3. Update and upgrade your raspberrry: sudo apt update && sudo apt upgrade
4. Install command: wget -O - https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install | sudo bash
5. Reboot: sudo reboot
6. Now you can open your browser and type rpi ip address
7. Default login and password for OMV panel is:
login: admin 
password: openmediavault
