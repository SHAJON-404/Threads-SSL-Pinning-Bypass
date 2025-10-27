# 🔐 Threads-SSL-Pinning-Bypass
📡 Intercept Threads network traffic on Android device/emulator

## 📌 Latest Tested App Version
- 🎯 Threads App version: **404.0.0.30.76**
- 🏗️ Architecture: **arm64**, **armv7**, **x86**, **x86_64**

![main desktop](https://raw.githubusercontent.com/SHAJON-404/Threads-SSL-Pinning-Bypass/refs/heads/main/image/v404.jpg)

## Requirements for Mobile Phone
 1. Rooted Andriod Phone [possible non root also]
 2. ProxyPin or Reqable App

## Requirements for Emulator
1. Windows PC with Reqable/ Burpsuit/ Mitmproxy installed  
2. Android emulator (Nox/LDPlayer)  
3. Root access on emulator  

## Process
 1. replace patched `libstartup.so` with `/data/data/com.instagram.barcelona/lib-compressed/libstartup.so`
 2. Command  ```adb push D:\patched\libstartup.so /data/data/com.instagram.barcelona/lib-compressed/libstartup.so```
 3. run proxypin or reqable app to capture traffic :)

## Looking for leatest version patched `libstartup.so`? Contact me on Telegram
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>

