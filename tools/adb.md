# adb

## 无线调试
  1. `adb tcpip 5555`            -> listening for connections on port 5555
  2. devices ip address 
   ```
    adb shell netcfg
    adb shell ifconfig       -> 6.0 and highe
    adb shell ip addr show
   ```
  3. `adb disconnect <usb devices>`
  4. `adb connect <ip address>:5555`
- `adb usb`                      -> 断开无线调试，用回usb
- `adb -s <ip address>:5555 usb` -> 断开多个设备中的某个连接
