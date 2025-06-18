Here's an improved version of your README.md with better formatting, structure, and clarity while maintaining all the original content:

```markdown
# HACK-CAMERA 🎥
###### A camera phishing tool with Cloudflare and ngrok tunneling

![HACK-CAMERA Preview](https://i.postimg.cc/3wJP9w39/Screenshot-2025-06-18-08-47-13.png)

> **Warning**: This tool is for educational purposes only. Please use responsibly.

## 🌟 Features
- **Multiple Templates**: 3 included (more coming soon)
- **Target Information**: Captures IP, location, device type, and browser
- **Dual Tunneling**: Choose between Cloudflare or ngrok
- **Custom Storage**: Save images to your preferred directory
- **Error Diagnoser**: Built-in troubleshooting
- **Argument Support**: Customize templates, tunnelers, and directories

## 🖥️ Supported Platforms
- Kali Linux
- Termux
- MacOS
- Ubuntu
- Parrot Sec OS
- Garuda Linux

## 🛠️ Installation

### Termux/Kali Linux:
```bash
apt update && apt upgrade -y
apt install git php curl wget -y
git clone https://github.com/hacker2108-maker/HACK-CAM.git
cd HACK-CAM
chmod +x hack-cam.sh  
chmod +x setup
./setup
./hack-cam.sh
```

### Additional for Termux:
```bash
termux-setup-storage
```

## 📹 How It Works
1. Hosts a phishing site on your local network
2. Uses port forwarding (Cloudflare or ngrok) to expose the site
3. Generate and send a link to target
4. When opened:
   - Captures target's IP information
   - Requests camera access
   - Takes sequential photos upon permission
   - Sends images to your server

## ⚠️ Important Notice
This tool demonstrates camera phishing techniques for **educational purposes only**. Unauthorized access to devices is illegal. The developer assumes no responsibility for misuse.

## 💻 Technologies Used
- Bash Scripting
- HTML/CSS/JavaScript
- PHP
- Cloudflare/ngrok integration

## 👥 Community
[Join our Youtube](https://youtube.com/@fsociety-v7s?si=xpFO78pa4NBMa0ce)

> "With great power comes great responsibility" - Please use ethically
```

Key improvements:
1. Better visual hierarchy with emojis and sections
2. More professional tone while keeping original content
3. Combined installation commands for efficiency
4. Clearer feature descriptions
5. Improved disclaimer visibility
6. Better formatting for code blocks
7. Added "quote" for ethical reminder
8. More organized structure overall

