# 🐬 A FlipperZero BadKB Script to pull lot of info from connected pc and sends to a Discord Webhook 🌐

## 📝 Description
This project includes a Flipper Zero (Rubber Ducky) script 🦆 and a PHP script 🖥️ designed to collect system information from a Windows computer 💻 and send it to a Discord channel via a webhook 📤. The Rubber Ducky script gathers details like the computer's name, hardware ID, IP address, and Windows version, along with additional IP-related information using the ipinfo.io API 🌍. The PHP script then formats this data and forwards it to a Discord channel 📬. ( Its Wolf Of Wall street themed Webhook :> )

## 🧩 Components
- **Rubber Ducky Script**: 🦆 Collects data from a Windows computer.
- **PHP Script**: 🖥️ Receives data, formats it, and sends it to Discord.

## 🌟 Features
- Retrieves key system and network information 🌐.
- Uses ipinfo.io for additional IP data 📍.
- Customizable Discord webhook integration 🎨.

## 📦 Requirements
- Flipper Zero Either on CFW or OFW / USB Rubber Ducky or similar device 🦆.
- Web server with PHP 🌐.
- Discord server with a configured webhook 🔗.

## ⚙️ Installation and Setup

### Rubber Ducky Script
1. Make sure your flipper is running a stable update 🔧.
2. Copy the script to the Flipper's BadUSB folder on your sD card 📂.
3. Modify the script with your PHP script URL 📝.

### PHP Script
1. Upload the PHP script to your web server 🚀. ( host free ones at https://www.000webhost.com/ )
2. Configure your Discord webhook URL in the script 🔗.

## 🚀 Usage
- Insert the Rubber Ducky into a Windows computer 💻.
- Data is sent to the PHP script and then to Discord 📤.

## ⚠️ Disclaimer
Use responsibly and legally 🚨. Ensure you have permission to run this script on the target computer 🖥️.

## 🙅‍♂️ Important Notes
Legal and Ethical Considerations: It's crucial to use this script responsibly. Ensure you have explicit permission to run this script on any computer. Unauthorized use may violate privacy and computer misuse laws.
Testing: Before deploying, thoroughly test the script in a controlled environment to ensure it functions as expected.
Security: Be aware of the security implications of running such scripts and hosting PHP scripts that receive and process data.
