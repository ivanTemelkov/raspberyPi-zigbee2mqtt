# Install Zigbee2Mqtt on Raspbery Pi 2 (Model B Rev 1.1) with WiFi dongle rtl8192eu

 1. Install Raspberry Pi OS Lite:
    https://www.raspberrypi.com/software/operating-systems/
 2. (Optional) Enable SSH using raspi-config
 3. Use LAN connection and install the rtl8192eu-linux driver:
    https://github.com/clnhub/rtl8192eu-linux
 4. Use raspi-config to configure the WiFi access.
 5. Install a recent version of NodeJs (https://thisdavej.com/upgrading-to-more-recent-versions-of-node-js-on-the-raspberry-pi/)
 
 <code>curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install nodejs</code>

 6. Install Mosquitto Broker ([link](https://randomnerdtutorials.com/how-to-install-mosquitto-broker-on-raspberry-pi/))
 7. 
