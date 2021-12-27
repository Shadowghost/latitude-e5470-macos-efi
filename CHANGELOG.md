## OC 0.7.6 EFI r001

### config.plist

- Added entries for all ACPI patches
- Added entries for all drivers
- Added entries for all kexts
- Added entries for all tools
- Added remaining entries to make the EFI work (too many to list)

### ACPI

- Added **SSDT-BRT6.aml**
- Added **SSDT-EC-USBX-LAPTOP.aml**
- Added **SSDT-GPRW.aml**
- Added **SSDT-HPET.aml**
- Added **SSDT-PLUG-DRTNIA.aml**
- Added **SSDT-PNLF.aml**
- Added **SSDT-XOSI.aml**

### Drivers

- Added **AudioDxe.efi**
- Added **CrScreenshotDxe.efi**
- Added **HfsPlus.efi**
- Added **OpenCanopy.efi**
- Added **OpenRuntime.efi**

### Kexts

- Added **AirportItlwm.kext** 2.1.0 RC1
- Added **AppleALC.kext** 1.6.7
- Added **BlueToolFixup.kext** 2.6.1
- Added **BrightnessKeys.kext** 1.0.2
- Added **FeatureUnlock.keyt** 1.0.4
- Added **IntelBluetoothFirmware.kext** 2.1.0 RC1
- Added **IntelMausi.kext** 1.0.7
- Added **Lilu.kext** 1.5.8
- Added **NVMeFix.kext** 1.0.9
- Added **Sinetek-rtsx.kext** 9.0
- Added **SMCBatteryManager.kext** 1.2.8
- Added **SMCDellSensors.kext** 1.2.8
- Added **SMCProcessor.kext** 1.2.8
- Added **USBPorts.kext** (customized)
- Added **VerbStub.kext** (no idea where I sourced it from)
- Added **VoodooPS2Controller.kext** 2.2.7
- Added **VirtualSMC.kext** 1.2.8
- Added **WhateverGreen.kext** 1.5.5

### Tools

- Added **memtest86**
- Added **Nvram.efi**
- Added **ControlMsrE2.efi**
- Added **OpenShell.efi**
- Added **ResetSystem.efi**

### Misc

- Added OC binary tools
- Added BigSurFlat OpenCanopy theme

### Notes

Before using this EFI, replace the following _PlatformInfo > Generic_ values in _config.plist_ with your own (use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)):

- MLB
- ROM
- SystemSerialNumber
- SystemUUID

This EFI is meant to be used with macOS 12 Monterey.
