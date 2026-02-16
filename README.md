# 🚀 TimeCapsule-Pi - Easy Backups for Your macOS

[![Download](https://img.shields.io/badge/Download-TimeCapsule--Pi-blue.svg)](https://github.com/ilhamnurramdani/TimeCapsule-Pi/releases)

## 📄 Introduction

TimeCapsule-Pi helps you turn your Raspberry Pi into a powerful backup server for your macOS devices. This application effectively replaces Apple Time Capsule using Samba, Avahi, and vfs_fruit support. It gives you a simple, effective way to keep your important data safe.

## 📦 Features

- **Easy Setup:** Follow straightforward instructions to get your backup server up and running.
- **Samba Support:** Share files easily across different systems.
- **Avahi Integration:** Discover devices and services on your local network without the need for configuration.
- **macOS Compatibility:** Works seamlessly with Mac for backing up data.
- **Data Security:** Keep your backups secure and reliable.

## 💻 System Requirements

- **Hardware:** Raspberry Pi 2, 3, or 4.
- **Operating System:** Raspbian or any other compatible Linux distribution.
- **Network:** Reliable internet connection for downloading and setting up.

## 🚀 Getting Started

Follow these steps to set up your TimeCapsule-Pi.

1. **Prepare Your Raspberry Pi:**
   - Ensure you have the latest version of Raspbian installed.
   - Connect your Pi to your network via Ethernet or Wi-Fi.

2. **Visit the Releases Page:**
   - Head to our [Releases page](https://github.com/ilhamnurramdani/TimeCapsule-Pi/releases) to get the latest version.

3. **Download the Software:**
   - Click on the latest release, and download the provided file. Follow the link below to ensure you’re getting the right version:  
   [Download TimeCapsule-Pi](https://github.com/ilhamnurramdani/TimeCapsule-Pi/releases).

4. **Install the Required Packages:**
   - Open your terminal and enter the following commands:
     ```bash
     sudo apt-get update
     sudo apt-get install samba avahi-daemon
     ```

5. **Configure the Application:**
   - After downloading, extract the files. Open a terminal and navigate to the directory where you saved it.
   - Locate the configuration file and adjust settings according to your network setup.

6. **Start the Backup Server:**
   - Run the application with the following command:
     ```bash
     sudo ./start-server.sh
     ```

7. **Connect Your macOS Device:**
   - On your Mac, open Finder.
   - Under “Shared,” you will see your Raspberry Pi. Click on it and connect.

## 🔧 Download & Install

To get started, visit our [Releases page](https://github.com/ilhamnurramdani/TimeCapsule-Pi/releases) and download the latest version. Upon downloading, follow the steps outlined in the "Getting Started" section to install and configure the application.

## ❓ Frequently Asked Questions (FAQs)

### 1. How do I remove TimeCapsule-Pi?

If you wish to uninstall, simply stop the server and remove the files from your Raspberry Pi.

### 2. Can I use an external hard drive?

Yes, connecting an external hard drive to your Raspberry Pi allows for larger backups. Make sure to mount it correctly before starting the server.

### 3. What if I encounter problems during setup?

You can check for solutions in the [Issues section](https://github.com/ilhamnurramdani/TimeCapsule-Pi/issues) of our GitHub repository. You can submit your questions there if you need further assistance.

### 4. Is there a way to automate backups?

Yes, you can schedule backups using cron jobs in Linux for regular intervals. Consult Linux guides on cron for setup instructions.

## 🌐 Community and Support

Join our community on GitHub to share your experience or seek help. We encourage feedback, feature requests, and contributions to improve TimeCapsule-Pi.

## 🔗 Links

- [Releases Page](https://github.com/ilhamnurramdani/TimeCapsule-Pi/releases)
- [Documentation](https://github.com/ilhamnurramdani/TimeCapsule-Pi/wiki)
- [Issues & Support](https://github.com/ilhamnurramdani/TimeCapsule-Pi/issues)

By following these steps and utilizing the resources above, you will easily set up your TimeCapsule-Pi. Enjoy a reliable and effective backup solution for your macOS devices!