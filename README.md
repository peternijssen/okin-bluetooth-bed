# okin-bluetooth-bed
This repository contains an ESPHome configuration for controlling beds with bluetooth OKIN / Okimat motors. Specially this has been tested with motors with the following specs:
* **Manufacturer:** DewertOkin GmbH
* **Model:** OKIMAT 4 IPS
* **Software Revision:** 93553
* **Hardware Revision:** 88542

I couldn't have figured everything out without the help of libraries like [smartbed-mqtt](https://github.com/richardhopton/smartbed-mqtt). Consider using this home-assistant add-on first before reverting back to this native integration. For me it didn't work well unfortunately at this point.

I also got a lot of information from the Home Assistant Community, especially [this topic](https://community.home-assistant.io/t/how-to-setup-esphome-to-control-my-bluetooth-controlled-octocontrol-bed/540790). I've been using work from others to be able to compose this entire set-up.


