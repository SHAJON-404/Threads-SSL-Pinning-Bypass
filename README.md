# 🔐 Threads-SSL-Pinning-Bypass
📡 Intercept Threads network traffic on Android device

## 📌 Latest Bypass & Tested App Version
- 🎯 Threads version: **421.0.0.50.67**
- 🎯 Edits version: **421.0.0.57.66**
- Architecture: **arm64-v8a, X86_64**
- For any inquiries, please contact me on Telegram [https://t.me/DarknessKing999](https://t.me/DarknessKing999)

## 🎥 Evidence
- **Threads:**
![Threads Android](assets/v421.jpg)

- **Edits:**
![Edits Android](assets/v421_edits.jpg)

## ✅ Other Apps
1. [Threads iOS](https://github.com/shajon-dev/iOS-Threads-SSL-Pinning-Bypass)
2. [Facebook Android](https://github.com/shajon-dev/Facebook-SSL-Pinning-Bypass)
3. [Facebook iOS](https://github.com/shajon-dev/iOS-Facebook-SSL-Pinning-Bypass)
4. [Messenger Android](https://github.com/shajon-dev/Messenger-SSL-Pinning-Bypass)
5. [Messenger iOS](https://github.com/shajon-dev/iOS-Messenger-SSL-Pinning-Bypass)
6. [Instagram Android](https://github.com/shajon-dev/Instagram-SSL-Pinning-Bypass)
7. [Instagram iOS](https://github.com/shajon-dev/iOS-Instagram-SSL-Pinning-Bypass)
8. [Business Suite Android](https://github.com/shajon-dev/Meta-Business-Suit-SSL-Pinning-Bypass)

## 📱 Requirements
1. 🔓 Rooted Android phone or Emulator with root access (ldplayer9 / nox player)
2. 🛠️ ADB tools installed on your computer
3. 🔄 Mitmproxy or Reqable App for traffic capture

## 🔧 Setup Process
 1. 🔧 **Replace patched `libstartup.so`** with the original file at: `/data/data/com.instagram.barcelona/lib-compressed/libstartup.so`
 2. 📲 **Use ADB command** to push the patched library:
    ```
    adb push D:\patched\libstartup.so /data/data/com.instagram.barcelona/lib-compressed/libstartup.so
    ```
 4. Use any packet capture tool to monitor Threads network traffic.

## 📦 For Demo - Download Official APKs
**📥 Download Threads 390.0.0.40.81 from official sources:**

- **🔧 arm64-v8a (64-bit):** [https://www.apkmirror.com/apk/instagram/threads-an-instagram-app/threads-390-0-0-40-81-release/threads-390-0-0-40-81-android-apk-download/](https://www.apkmirror.com/apk/instagram/threads-an-instagram-app/threads-390-0-0-40-81-release/threads-390-0-0-40-81-android-apk-download/)

- **🔧 x86_64 (64-bit emulator):** [https://www.apkmirror.com/apk/instagram/threads-an-instagram-app/threads-390-0-0-40-81-release/threads-390-0-0-40-81-8-android-apk-download/](https://www.apkmirror.com/apk/instagram/threads-an-instagram-app/threads-390-0-0-40-81-release/threads-390-0-0-40-81-8-android-apk-download/)

**📂 Free Patched `libstartup.so` files are available in the `libs/` folder**
**📜 Consolidated login scripts are available in the `login.sh` file**

## Looking for leatest version patched `libstartup.so`? Contact me on Telegram
<p align="left">
  <a href="https://t.me/DarknessKing999" target="_blank">
    <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
  </a>
</p>
