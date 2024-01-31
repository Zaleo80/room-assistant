# What is RoomAssistant:

An open source easy to deploy optimized solution to cover the [Home Assistant](https://www.home-assistant.io/) features in every room.

## The mission:
Every serious smart-house running [Home Assistant](https://www.home-assistant.io/) has a unit running this image in each of its rooms.

## How are we going to do this:
- Eazy to deploy and use
- By bringing together the best of multiple existing projects into one custom image
- Supporting the most common and affordable hardware peripherals
- Highly Configurable
- Seamless home-assistant integration

Hopefully, in the future we could extend to other boards, but for now we will focus on the [Raspberry Zero v2 W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/) board.

We are planning to include:

| **Function** | **Hardware peripherals** | **Software** | **Status** |
| :---:   | :---: | :---: | :---: |
| Voice Assistant | [RESpeak 2-mic hat](https://www.seeedstudio.com/ReSpeaker-2-Mics-Pi-HAT.html) | [wyoming-satellite](https://github.com/rhasspy/wyoming-satellite) | ❌ |
| Multiroom audio streaming | Any audio Playback Device | [snapcast](https://www.home-assistant.io/blog/2016/02/18/multi-room-audio-with-snapcast/) | ❌ |
| Remote-GPIO | None | [remote_rpi_gpio](https://github.com/home-assistant/core/tree/dev/homeassistant/components/remote_rpi_gpio) | ❌ |
| Camera | [CSI-2 Camera Module v3](https://www.raspberrypi.com/products/camera-module-3/) | [Motion?](https://motion-project.github.io/index.html) | ❌ |
| Camera | USB-Webcam | [Motion?](https://motion-project.github.io/index.html) | ❌ |
| Room occupancy | PIR and/or mmWave | TBD | ❌ |
| Room presence | None | ESPresence | ❌ |
| Room atmosphere | [PM2.5, CO2, VOC, Temp & Hum.](https://howtomechatronics.com/projects/diy-air-quality-monitor-pm2-5-co2-voc-ozone-temp-hum-arduino-meter) | TBD | ❌ |
| Bluetooth Proxy | None | * | ❌ |

 *There is only software available for microcontrollers not for Linux, as far as I know.
