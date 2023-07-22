#!/bin/bash

# Use nmcli to connect to a custom wifi network
# Replace network-ssid and network-password with your own values
sudo nmcli dev wifi connect network-ssid password "network-password"

# Download brave browser for Kali Linux
# Add the brave keyring to the system
sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg

# Add the brave repository to the sources.list.d file
echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser-release.list

# Update the system repository list
sudo apt update

# Install brave browser
sudo apt install brave-browser
