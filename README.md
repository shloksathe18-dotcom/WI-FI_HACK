# 🔐 Wi-Fi Password Extractor

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/License-Educational-green.svg)

**A Python script that extracts saved Wi-Fi passwords from Windows systems**

[🔗 GitHub Repository](https://github.com/shloksathe18-dotcom/WI-FI_HACK)

</div>

---

## 📋 Description

This educational tool demonstrates how to retrieve saved Wi-Fi network profiles and their passwords from Windows systems using the built-in `netsh` command-line utility. Perfect for learning about Windows network management and system administration.

## ✨ Features

- 📡 **Profile Discovery**: Lists all saved Wi-Fi profiles on the system
- 🔑 **Password Extraction**: Retrieves stored network credentials
- 🛡️ **Error Handling**: Gracefully manages encoding and access errors
- 📊 **Clean Output**: Formatted display of network names and passwords
- 🎯 **Educational Focus**: Designed for learning network security concepts

## 🚀 Quick Start

### Prerequisites
- Windows operating system
- Python 3.x installed
- Command prompt or PowerShell

### Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shloksathe18-dotcom/WI-FI_HACK.git
   cd WI-FI_HACK
   ```

2. **Run the script:**
   ```bash
   python WI-FI_HACK.py
   ```

3. **View results:**
   ```
   Network_Name                  |  Password
   MyHomeWiFi                    |  mypassword123
   GuestNetwork                  |  
   CorporateWiFi                 |  [Hidden/Encrypted]
   ```

## 🔧 How It Works

The script utilizes Windows' built-in `netsh` utility to:
1. Query all stored wireless profiles
2. Extract profile details including security keys
3. Format and display the information in a readable format

## 📚 Educational Value

This project helps students and professionals understand:
- Windows network profile management
- Command-line utilities and subprocess handling
- Network security concepts
- Python system administration scripting

## ⚠️ Important Notes

- 🖥️ **Windows Only**: This tool is specifically designed for Windows systems
- 👤 **User Scope**: Only retrieves passwords for networks the current user has accessed
- 🔐 **Permissions**: Administrator privileges may be required for complete profile access
- 🚫 **Encoding Issues**: Some networks may display errors due to special characters

## 📖 Educational Use Only

> **🎓 EDUCATIONAL PURPOSE DISCLAIMER**
> 
> This tool is created **exclusively for educational purposes** to help students and professionals learn about:
> - Network security concepts
> - Windows system administration
> - Python scripting for system tasks
> - Cybersecurity awareness
> 
> **Always use this tool responsibly and only on networks you own or have explicit permission to test.**

## ⚖️ Legal & Ethical Guidelines

- ✅ **Authorized Use Only**: Use only on your own networks or with explicit written permission
- ✅ **Educational Context**: Perfect for cybersecurity courses and workshops
- ✅ **Responsible Disclosure**: Report vulnerabilities through proper channels
- ❌ **No Unauthorized Access**: Never use on networks without permission
- ❌ **No Malicious Intent**: This tool is not for illegal activities

## 👨‍💻 Credits & Attribution

<div align="center">

**Created by: [Shlok](https://github.com/shloksathe18-dotcom)**

[![GitHub](https://img.shields.io/badge/GitHub-shloksathe18--dotcom-black.svg?logo=github)](https://github.com/shloksathe18-dotcom)

</div>

---

<div align="center">

**⭐ If this project helped you learn something new, please give it a star! ⭐**

*Remember: With great power comes great responsibility. Use your knowledge ethically.*

</div>
