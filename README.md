# ESP8266 Fake Captive Portal
The **ESP8266 Fake Captive Portal** is tool designed to streamline the process of connecting devices to a Wi-Fi network. By acting as an intermediary, this captive portal captures and saves Wi-Fi network credentials directly to the internal memory of the microcontroller. It can be used for Wi-Fi penetration testing, helping to identify vulnerabilities in network security by mimicking a legitimate access point and capturing sensitive data such as Wi-Fi passwords.

# Usage

This is how you can access the following HTTP endpoint
- `http://192.168.1.10`
  > To access the main portal
  
- `http://192.168.1.10/ssid`
  > This endpoint allows you to change the SSID based on your target.

- `http://192.168.1.10/localip`
  > To find out the local IP address when connected to a Wi-Fi network.


# Differences from other ESP8266 Captive Portal
This version allows you to access the ESP8266 captive portal through the network and easily check the password list if you have victims. There's no need to connect to the ESP8266's default gateway. This makes it more efficient in terms of accessibility.

# Images of the ESP8266 Fake Captive Portal

**Default Gateway:**
![](https://github.com/PhitzZ/esp8266-captive-portal/blob/main/Images/Default%20Gateway.png)

**Network Gateway:**
![](https://github.com/PhitzZ/esp8266-captive-portal/blob/main/Images/Network%20Gateway.png)

# Disclaimer
This project is a proof of concept for testing and educational purposes.


Use it only against your own networks and devices!
Please check the legal regulations in your country before using it. 
We don't take any responsibility for what you do with this program.
