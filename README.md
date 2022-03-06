# Ninja_Server_Termux
Ninja School Server on Termux Android
# Version: 2.5
# Update: 20/02/2022

#
# 1Tech-X & KhanhNguyen9872
#

# System Requirements
CPU: Quad-core with 1.00GHz or up <br />

Architecture: 64bit only [arm64-v8a] <br />

Android 7.0 Nougat or up <br />

RAM: 2GB or up <br />

Internal storage: 3GB free space <br />

Termux: Latest version! <br />

# Note

Server cannot be start if port 3306, 8080 is in used! <br />

Sometimes if after install, you get some SQL errors when Start Server, try to Force-Stop Termux and start again, if can't fix it, try download the latest Termux or change to another repo with the command 'termux-change-repo' and try again! <br />


# How to install?
 - Tutorial: https://www.youtube.com/watch?v=f9YiOHyBAcI
1. Download Termux APK (click on Picture): 
[![](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/raw/main/image/termux.png)](https://f-droid.org/repo/com.termux_118.apk)
 or 
[![](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/raw/main/image/termux.png)](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/releases/download/NinjaServerTermuxv01/termux_0.118.apk)

2. Install Termux APK

3. Open Termux, copy this line and paste it on Termux

```
pkg install wget -y && wget -O install.sh https://raw.githubusercontent.com/KhanhNguyen9872/Ninja_Server_Termux/main/install.sh && bash install.sh
```
4. Wait for a long time!
 
5. After Download 4xx MB and Install, Termux will ask you something, do it!

6. Choose Source you want to use! 
 
7. Enjoy!
# HOW TO CHANGE SOURCE?
1. Open Termux and run this command
```
tamp -start
```
2. Open New Session and run this command
```
menu
```
3. Choose Settings, and Choose 'Change Source'

4. Restart Termux!

# How to start?
1. Open Termux and run this command
```
tamp -start
```
2. Next, open New Session Termux and run this command
```
ninja
```
3. Open J2ME-Loader and Enjoy it!

# Next if you want to register account Ninja School
Open New Session Termux, run this command
```
menu
```

# IF You don't see Ninja School in J2ME-Loader
 - Install ninja.jar file [using J2ME-Loader] and Enjoy!
```
ninja-Khanh.jar in /sdcard [Internal Storage]
```
