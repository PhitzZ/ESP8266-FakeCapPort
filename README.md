# ESP8266 FAKE CAPTIVE PORTAL
The **ESP8266 Captive Portal** is tool designed to streamline the process of connecting devices to a Wi-Fi network. By acting as an intermediary, this captive portal captures and saves Wi-Fi network credentials directly to the internal memory of the microcontroller. It can be used for Wi-Fi penetration testing, helping to identify vulnerabilities in network security by mimicking a legitimate access point and capturing sensitive data such as passwords, allowing network administrators to strengthen their defenses.

# Usage

This is how you can access the following HTTP endpoint
- `http://192.168.1.10`
  > To access the main portal
  
- `http://192.168.1.10/ssid`
  > This endpoint allows you to change the SSID based on your target.

- `http://192.168.1.10/localip`
  > To find out the local IP address when connected to a Wi-Fi network.


# Differences from other ESP8266 Captive Portal
This version allows you to access the ESP8266 captive portal through the network and easily check the password list if you have victims. There's no need to connect to the ESP8266's default gateway, making it more efficient in terms of accessibility.

# Images of the ESP8266 Fake Captive Portal
