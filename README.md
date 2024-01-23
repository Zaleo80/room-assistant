# room-assistant
Open source easy to deploy image(s) to cover the home-assistant basics in each room with the most common hardware.

The ulitmate goal is to provide an eazy to deploy image that brings together the best of multiple existing projects.
This immage should support the most common hardware used.

Hopefully, in the future we could extend to other boards, but for now we will focus on the Raspberry Zero v2 W board and the most used peripherals.

The image will include a pre-installed support for:

| Function | Hardware peripherals | Software | Status |
| :---:   | :---: | :---: | :---: |
| Voice Assistant | RESpeak 2-mic hat | https://github.com/rhasspy/wyoming-satellite | ❌ |
| Multiroom audio streaming | Audio Playback Device | https://www.home-assistant.io/blog/2016/02/18/multi-room-audio-with-snapcast/ | ❌ |
| Remote-GPIO | None | https://github.com/home-assistant/core/tree/dev/homeassistant/components/remote_rpi_gpio | ❌ |
| Camera | USB-CAM / CSI-2 camera | https://github.com/Motion-Project/motion | ❌ |
| Room occupancy | PIR and/or mmWave | ? | ❌ |
| Room presence | None | ESPresense? | ❌ |
| Bluethooth Proxy| None |  | ❌ |
