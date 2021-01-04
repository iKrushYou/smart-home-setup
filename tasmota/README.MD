### Flash Switch
- Follow tuya-convert instructions, install tasmota

### Connect to Wi-Fi
- Connect phone to hotspot and configure Wi-Fi

### Update Firmware
- OTA update to latest minimal (since regular is too large)
http://ota.tasmota.com/tasmota/release/tasmota-minimal.bin
- OTA update to latest regular build
http://ota.tasmota.com/tasmota/release/tasmota.bin

### Configure Tasmota
- Update settings based on [config json](https://github.com/iKrushYou/smart-home-setup/blob/main/tasmota/treatlife-switch-config)
```json
{"NAME":"Treatlife Switch","GPIO":[0,0,0,0,288,576,1,1,224,160,0,0,0,1],"FLAG":0,"BASE":18}
```
- SwitchMode 3
