# Install Zigbee2Mqtt on Raspbery Pi 2 (Model B Rev 1.1) with WiFi dongle rtl8192eu

This is not intended to be detailed step by step guide on how to install all the needed software components, but rather a collection of usefull links that did the work on my hardware starting from the Lite OS version.

 1. Install Raspberry Pi OS Lite ([link](https://www.raspberrypi.com/software/operating-systems/)):
 2. (Optional) Enable SSH using raspi-config
 3. Use LAN connection and install the rtl8192eu-linux driver ([link](https://github.com/clnhub/rtl8192eu-linux)):
 4. Use raspi-config to configure the WiFi access.
 5. Install a recent version of NodeJs ([link](https://thisdavej.com/upgrading-to-more-recent-versions-of-node-js-on-the-raspberry-pi/))
 
 <code>curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install nodejs</code>

 6. Install Mosquitto Broker ([link](https://randomnerdtutorials.com/how-to-install-mosquitto-broker-on-raspberry-pi/))
 7. Install Zigbee2mqtt ([link](https://www.zigbee2mqtt.io/guide/installation/01_linux.html))
 8. Install Node-RED ([link](https://nodered.org/docs/getting-started/raspberrypi))
     1. Install Node-RED Dashboard ([link](https://flows.nodered.org/node/node-red-dashboard))
     2. Install Node-RED Timer ([link](https://flows.nodered.org/node/node-red-contrib-timer))
     3. Install Node-RED Zigbee2mqtt ([link](https://flows.nodered.org/node/node-red-contrib-zigbee2mqtt))
     4. Install Node-RED Telegram Bot ([link](https://flows.nodered.org/node/node-red-contrib-telegrambot))
