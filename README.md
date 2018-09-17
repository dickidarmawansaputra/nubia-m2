# Nubia M2

Installation LineageOS 14.1 (or other custom ROM) in Nubia M2

## Getting Started

These instructions will get you how to install LineageOS 14.1 (or other custom ROM) in Nubia M2

### Installation Requirements

<ul>
	<li><a href="https://drive.google.com/file/d/1YSdAOY0wEyDojF24G7jeDhDdxwy3yr8Q/view">Lineage OS 14.1</a></li>
	<li><a href="http://ui.nubia.cn/rom/detail/36">Nubia M2 Chinese ROM</a></li>
	<li><a href="http://download930.mediafire.com/dmm09bpd33wg/ccnnv843a20tqbn/minimal_adb_fastboot_v1.4.3.zip">Minimal ADB and Fastboot</a></li>
	<li><a href="https://dl.twrp.me/NX551J/twrp-3.2.3-0-NX551J.img">TWRP</a></li>
</ul>

### Installing

Step by step to installation

1. Install Nubia M2 chinese ROM via Nubia Recovery
2. Activated Developer Mode in Nubia M2 Chinese ROM and Enable **USB DEBUGGING AND UNLOCK OEM**
3. Install Minimal ADB and Fastboot
4. Copy or Paste TWRP Recovery Image to Minimal ADB and Fastboot Folder Installation

```
C:\ Program Files (x86)\Minimal ADB and Fastboot
```

5. Run as Administrator Minimal ADB and Fastboot

```
cmd-here.exe
```

6. Connect your Android device to the PC. Type the following into the command window to boot your device into bootloader/fastboot mode

```
adb reboot bootloader
```

7. Once your device boots into bootloader mode, type this into the command line

```
fastboot flash recovery twrp-3.2.3-0-NX551J.img
```

8. Once TWRP is successfully flashed on your device, type this final command to reboot your device.

```
fastboot reboot
```

9. Enter TWRP Mode to Flash Lineage OS 14.1 ROM

```
power button + volume up button
```

10. Done!

## Authors

* **Dicki Darmawan Saputra** - *Initial work* - [dickidarmawansaputra](https://github.com/dickidarmawansaputra)