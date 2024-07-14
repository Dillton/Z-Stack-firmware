# Z-Stack-firmware
Test repo with test "CC1352P2_CC2652P_launchpad_coordinator_*" firmwares for flashing coordinator through "ZigStar TI CC2652P/P7 FW Flasher" HA add-on.

Add-on config:
device: >-
  /dev/serial/by-id/usb-Silicon_Labs_Sonoff_Zigbee_3.0_USB_Dongle_Plus_0001-if00-port0
network_device: 127.0.0.1
usb_mode: true
sonoff: true
launchpad_fw: false
cc1352p7_fw: false
other_fw: false
firmware_url: >-
  https://github.com/Dillton/Z-Stack-firmware/blob/main/CC1352P2_CC2652P_launchpad_coordinator_20240710.zip
trigger_bsl: false
