# HTML JS MQTT Tool

This is a simple HTML and JavaScript MQTT tool that allows you to connect to an MQTT broker, subscribe to a topic, and send messages. It was written by Alex Leong from VYROX IoT.

## Updates
11-Aug-2023: Added the very important "Send/Receive in HEX".

## Usage

1. Open the HTML file in a web browser.
2. Select the MQTT broker (server) you want to connect to by choosing one of the radio buttons provided: test.mosquitto.org, broker.emqx.io, public.mqtthq.com, or Other (to enter a custom server).
3. Enter the hostname and port of the MQTT broker you want to connect to. The default values are already provided for the selected MQTT brokers.
4. Click the "Connect" button to establish a connection with the MQTT broker.
5. If the connection is successful, you can subscribe to a topic by entering the topic name in the "Topic" input field and clicking the "Subscribe" button. This will enable the "Send" button and allow you to send messages to the subscribed topic.
6. You can also unsubscribe from a topic by clicking the "Unsubscribe" button.
7. To disconnect from the MQTT broker, click the "Disconnect" button.

## Configuration

The tool provides several configuration options:

- **MQTT Broker (Server):** Choose the MQTT broker you want to connect to by selecting one of the radio buttons provided.
- **Hostname:** Enter the hostname of the MQTT broker.
- **Port:** Select the port number based on the encryption and authentication requirements of the MQTT broker.
- **Topic:** Enter the topic name you want to subscribe to or send messages to.
- **QoS (Quality of Service):** Select the desired QoS level for message delivery.
- **Retain:** Choose whether to retain messages on the MQTT broker.
- **Message:** Enter the message you want to send to the subscribed topic.

## Dependencies

This tool requires the following dependency:

- [`mqttws31.js`](https://www.cdnpkg.com/paho-mqtt/file/mqttws31.js/?id=59394): This JavaScript library provides the MQTT WebSocket implementation.

## Live Demo

You can try out the live demo of this tool at [![Live Demo](https://img.shields.io/badge/Live%20Demo-Click%20Here-brightgreen)](https://yeerock.000webhostapp.com/mqtt-tool-html-js/mqtt-tool-html-js.html)

## Credits

This tool was written by Alex Leong from VYROX IoT. For any issues or further information, please contact Alex Leong through [his page](https://vyrox.com/about.php).
