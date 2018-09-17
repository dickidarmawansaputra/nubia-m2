# Nubia M2

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation Requirements

<ul>
	<li><a href="https://drive.google.com/file/d/1YSdAOY0wEyDojF24G7jeDhDdxwy3yr8Q/view">Lineage OS 14.1</a></li>
	<li><a href="http://ui.nubia.cn/rom/detail/36">Nubia M2 Chinese ROM</a></li>
	<li><a href="http://download930.mediafire.com/dmm09bpd33wg/ccnnv843a20tqbn/minimal_adb_fastboot_v1.4.3.zip">Minimal ADB and Fastboot</a></li>
	<li><a href="https://dl.twrp.me/NX551J/twrp-3.2.3-0-NX551J.img">TWRP</a></li>
</ul>

### Installing

Step by step series of examples that tell you how to get a development env running

1. Install Nubia M2 Chinese ROM Via Nubia Recovery
2. Activated Developer Mode in M2 Chinese ROM and Enable **USB DEBUGGING AND UNLOCK OEM**
3. Install Minimal ADB and Fastboot
4. Connect USB Smartphone to Computer
5. Copy or Paste TWRP Recovery Image to Minimal ADB and Fastboot Folder Installation

```
C:\ Program Files (x86)\Minimal ADB and Fastboot
```

6. Run as Administrator Minimal ADB and Fastboot

```
cmd-here.exe
```

7. Connect your Android device to the PC. Type the following into the command window to boot your device into bootloader/fastboot mode

```
adb reboot bootloader
```

8. Once your device boots into bootloader mode, type this into the command line

```
fastboot flash recovery twrp-3.2.3-0-NX551J.img
```

9. Once TWRP is successfully flashed on your device, type this final command to reboot your device.

```
fastboot reboot
```

10. Enter TWRP Mode and Flash to Install Lineage OS 14.1

```
Power button + volume up
```

8. 
## Authors

* **Dicki Darmawan Saputra** - *Initial work* - [dickidarmawansaputra](https://github.com/dickidarmawansaputra)