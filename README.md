# Zigbee-IP-bridge-EFR32MG12-WF200
This example runs on BRD4163a + BRD8022a. EFR32 application uses BLE first to retrive Wifi credentials of an existing Wifi network. Application will then join this Wifi network and connect to an external server thourgh a TCP socket. Server address can be configured in file ##wifi/appsocket.c
