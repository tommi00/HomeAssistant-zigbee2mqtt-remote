# Zigbee2MQTT Remote

A project to integrate Zigbee remotes connected with Zigbee2MQTT on Home Assistant. 
This repository provides configuration files and scripts to facilitate the use of Zigbee remotes on Home Assistant, by letting you choose what every button does when clicked one, two or three times.

I suggest using those type of remote by LoraTap, which work really well: [Tuya Zigbee Remote](https://s.click.aliexpress.com/e/_o2cAT67).


## Features

- 🛠️ **Support for various Zigbee remotes**: Works with devices like the Tuya Zigbee Remote and others.  
- ⚙️ **Predefined configurations for easy setup**: Simplifies the integration process.  
- 🌐 **Seamless compatibility with Zigbee2MQTT and Home Assistant**: Ideal for your smart home setups.  

## Getting Started

### Prerequisites

Before starting, ensure you have:

- A Zigbee remote compatible with Zigbee2MQTT.
- A working Zigbee2MQTT environment.
- An MQTT broker for communication between ZIgbee2MQTT and Home Assistant.

### Installation

1. **Import the project in HA**:
- Go to "Settings" -> "Automations" -> Click on "Projects" tab.
- Click on "Import Project" button.
- Find on this repository the file you're interested,
- Copy the URL (for example, 6 buttons remote -> file "6 button" which URL is https://github.com/tommi00/HomeAssistant-zigbee2mqtt-remote/blob/main/6%20button ).
- Paste it in Home Assistant and click on the import button.
2. **Configure it**:
  Now you can you it as an Automation by configuring it: you can select the remote and assign an action to every button when clicked one, two or three times.
3. **Enjoy it!**:
  Save and share this project if you liked it!
