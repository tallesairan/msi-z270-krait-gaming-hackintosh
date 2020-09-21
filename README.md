# msi-z270-krait-gaming-hackintosh

Success MSI Z270 KRAIT GAMING | i7 7700k Catalina 10.15.6

## Hardware:

CPU: i7 7700k

GPU: Intel Graphics 630

RAM: 2x16GB Corsair Vengeance CMK32GX4M2D3200C16

Motherboard: MSI Z270 KRAIT GAMING / MSI B250 KRAIT GAMING ( i'm tested on both mb )

Audio Codec: Realtek® ALC1220 (Working)

Ethernet Card: Ethernet Intel® I219-V (working)

Wifi/BT Card: N/D

Touchpad and touch display devices: N/D

BIOS revision: 7A59vA9



## MSI BIOS Settings
Save & Exit → Restore Defaults : Yes
Advanced \ Integrated Peripherals → Network Stack : [Disabled]

Advanced \Integrated Peripherals  → Intel Serial IO : [Disabled]

Advanced \ USB Configuration → XHCI Hand-off : [Enabled]

Advanced \ USB Configuration → Legacy USB Support : [Auto]

Advanced \ Windows OS Configuration → MSI Fast Boot : [Disabled]

Advanced \ Windows OS Configuration → Fast Boot : [Disabled]

Overclocking  → Extreme Memory Profile(X.M.P) : [Enabled]

Overclocking \ CPU Features → Intel Virtualization Tech : [Enabled]

Overclocking \ CPU Features → Intel VT-D Tech : [Disabled]

Boot → Boot mode select : [LEGACY+UEFI]

bios/ after installing macOS

the debug mode is turned of and fastboot is turned on




## Clover revision: 5107

Kexts:

VirtualSMC.kext

SMCSuperIO.kext (v.1.1.6)

SMCProcessor.kext (v.1.1.6)

SMCLightSensor.kext (v.1.1.6)

SMCDellSensors.kext (v.1.1.6)

SATA-200-series-unsupported.kext (v.0.5.1)

AppleMCEReporterDisabler.kext (v.1.2)

FakePCIID_Intel_GbX.kext (v.1.3.15)

IntelGraphicsFixup.kext (v.1.2.7)

VoodooPS2Controller.kext (v.2.0.4)

VoodooPS2Controller.kext\Contents\PlugIns\VoodooPS2Mouse.kext.dSYM (v.2.0.4)

VoodooPS2Controller.kext\Contents\PlugIns\VoodooPS2Mouse.kext (v.2.0.4)

VoodooPS2Controller.kext\Contents\PlugIns\VoodooPS2Trackpad.kext.dSYM (v.2.0.4)

VoodooPS2Controller.kext\Contents\PlugIns\VoodooPS2Keyboard.kext (v.2.0.4)

VoodooPS2Controller.kext\Contents\PlugIns\VoodooPS2Trackpad.kext (v.2.0.4)

VoodooPS2Controller.kext\Contents\PlugIns\VoodooPS2Keyboard.kext.dSYM (v.2.0.4)

JMicron36xATA.kext (v.1.0.2)

AppleATIATA.kext (v.1.0.3)

FakePCIID_Broadcom_WiFi.kext (v.1.3.15)

FakePCIID.kext (v.1.3.15)

AppleHDA.kext (v.283.15)

AppleHDAController.kext (v.283.15)

DspFuncLib.kext (v.283.15)

AppleHDAHardwareConfigDriver.kext (v.283.15)

AppleMikeyDriver.kext (v.283.15)

IOHDAFamily.kext (v.283.15)

AppleRTL8169Ethernet.kext (v.1.1)

VoodooInput.kext (v.1)

AppleIntelKBLGraphicsFramebufferInjector_3e9x.kext (v.0.5.0)

Other\LiluFriend.kext (v.1.1.0)

Sinetek-rtsx.kext (v.1.0)

AtherosL1cEthernet.kext (v.1.0.1b9)

CPUFriend.kext (v.1.1.9)

USBInjectAll.kext (v.0.7.3)

RTCMemoryFixup.kext (v.1.0.4)

ApplePCIIDE.kext (v.1)

\BrcmNonPatchRAM2.kext (v.2.5.0)

AppleNForceATA.kext (v.1.0.4)

FakePCIID_XHCIMux.kext (v.1.3.15)

RealtekRTL8111.kext (v.2.2.2)

WhateverGreen.kext (v.1.3.7)

XHCI-200-series-injector.kext (v.0.5.0)

ATAPortInjector.kext (v.1.0.0)

SMCBatteryManager.kext (v.1.1.6)

CodecCommander.kext (v.2.6.3)

SATA-100-series-unsupported.kext (v.0.5.1)

IntelMausi.kext (v.1.0.2)

AtherosE2200Ethernet.kext (v.2.3.0)

SuperVIAATA.kext (v.1.0.3)

AppleALC.kext (v.1.5.0)

AttansicL1eEthernet.kext (v.1.0.1b0)

AtherosWiFiInjector.kext (v.1.0.1)

AirportBrcmFixup.kext (v.2.0.4)

XHCI-x99-injector.kext (v.0.5.0)

IOAHCIBlockStorageInjector.kext (v.1.1.1)

AHCIPortInjector.kext (v.1.0.1)

NoTouchID.kext (v.1.0.3)

SmallTreeIntel82576.kext (v.1.0.6)

BrcmFirmwareData.kext (v.2.5.0)

Lilu.kext (v.1.4.7)

AHCI_3rdParty_SATA.kext (v.0.4)
