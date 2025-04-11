# IPv4_Only_iOS
Generates an iOS profile to disable IPv6 functionality on cellular networks. 

One of the biggest drawbacks to using Wireguard profiles on iOS is that it leaks your IPv6 address when connected to a cellular network.

Most phone carriers hide the ability to edit APN settings, and this workaround will disable IPv6 for you to prevent IP leaks.

## Directions

1. Visit https://nickbly.com/IPv4/ on your iOS device
2. Select your wireless carrier from the list
3. Click "Generate IPv4-Only Profile"
4. Download the .mobileconfig file to your Files app
5. In the files app, tap on the file, and select which device to install to (if prompted)
6. Go to settings, select the downloaded profile, and install it
7. Your iOS device will no longer use IPv6 while connected to a cellular network
