# What engineers and developers should know about Wi-Fi 6

## What developers can do in WiFi 6 network

#### TWT(Target-Wakeup Time)
As explained on page 3, the device can control the time to pause the Wi-Fi connection by setting TWT. Since TWT is programmable, developers can program their apps to control the time to transmit data on Wi-Fi 6. You should be careful of the tradeoff between battery efficiency and traffic efficiency.

#### Controlling traffic
OFDMA supports dynamic allocation of subcarriers and DCM. So the traffic by clients can be regulated by its priority or reliability. For example, critical traffic like fire alarms can be transmitted by using DCM to overcome inferences and prevent loss.

## Types of apps which benefits from WiFi 6
#### VR/AR, streaming service
Wi-Fi 6 achieves great throughput(> 4 Gps) and low latency(< 10 ms). This enables users to use a real-time application like VR/AR, or streaming services with 4K.

#### low-power apps
Wi-Fi 6 provides energy saving via TWT and BSS Coloring. Developers can control battery efficiency by controlling TWT. This is especially effective for the app for low-battery IoT devices.


# Conclusion
Wi-Fi 6 makes the speed 40% faster than Wi-Fi 5 with 1024 QAM, 8x8 MU-MIMO, and OFDMA. But the key part is that Wi-Fi can deliver good quality of connection in a high-density area even as the number of users per AP increases, unlike prior versions. Also, it can achieve longer battery life with TWT and BSS Coloring. It is expected that Wi-Fi 6 provides a strong wireless network for the IoT space, AR/VR, or offloading mobile traffic.


## Reference
[Cisco IEEE 802.11ax Technical White Paper](https://www.cisco.com/c/dam/en/us/products/collateral/wireless/white-paper-c11-740788.pdf)
