# ESPuino firmwares

Provides for download ready-to-use firmwares for ESPuino. Some further informations can be found in the [ESPuino forum](https://forum.espuino.de/t/fertige-espuino-firmwares-zum-runterladen/3941). The following branches are supported:

* master: [Firmwares/master](https://github.com/biologist79/ESPuino-Firmware/tree/main/Firmwares/master)
* dev-branch: [Firmwares/dev](https://github.com/biologist79/ESPuino-Firmware/tree/main/Firmwares/dev)

> :warning: Filenaming is currently in transition. Rfid-reader will be omitted as reader's type is [autodetected at boot](https://forum.espuino.de/t/autoerkennung-von-rfid-reader/4453). We're currently about to investigate if BT should be activated permanentely. If this happens, BT/noBT will disappear as well.

Filenaming is as follows:  
firmware-{HAL}-{BT/noBT}.bin

While:

* {HAL}: Which HAL was used (e.g. [complete](https://forum.espuino.de/t/espuino-complete/3817) or [lolin_d32_pro_sdmmc_pe](https://forum.espuino.de/t/espuino-mini-4layer/1661))
* {BT/noBT}: Bluetooth is enabled or not
