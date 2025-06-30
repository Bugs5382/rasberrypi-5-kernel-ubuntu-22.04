# Raspberry Pi 5 - WaveShare 4.3" DSI Display Support

This project provides a custom Ubuntu 22.04.2 build (or newer) for the **Raspberry Pi 5**, preconfigured to support the **WaveShare 4.3" DSI LCD (800x480)** display. It includes a modern 6.6.x+ kernel and necessary drivers/modules to fully enable display output and touch support (if applicable) over the DSI interface.

## ✅ Features

* Raspberry Pi 5 support (64-bit ARM)
* Raspberry Ubuntu Server 22.04.2 LTS base image
* Raspberry Linux Kernel 6.6.y

## To Build

1) Clone Repo
2) Setup a Github Runner for Self-Hosted
3) Once Runner associated, trigger the workflow
4) Once completed, download the .img file.
5) Use RaspberryPI imager and select custom img. Do not use the OS Customizer for Wi-Fi or Password settings. You will need to use default username and password for Ubuntu OS.
6) Once you are logged in, update password, and enable Wi-Fi or Wired ethernet adaptor.


## WaveShare Build

1) Close WaveShare Repo - https://github.com/waveshare/Waveshare-DSI-LCD
2) Browse to 6.6.51/<64/32>/pi5
3) Using 'sudo' type: ```sudo ./WS_xinchDSI_MAIN.sh 34C I2C1```