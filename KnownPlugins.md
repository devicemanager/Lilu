Existing Lilu plugins
=====================

This for sure may not be a complete list. If you feel that something is missing, make an issue and it will be included.  
Please note that improperly written immature plugins will not be listed there.

| Name | Short description |
|:-----|:------------------|
[AirportBrcmFixup](https://github.com/devicemanager/AirportBrcmFixup) | Various patches for Broadcom Airport Wi-Fi cards
[AppleALC](https://github.com/devicemanager/AppleALC) | Native macOS HD audio for not officially supported codecs
[AMFIExemption](https://github.com/osy86/AMFIExemption) | Adds allowed entitlements to non-Apple signed apps when SIP is enabled
[ATH9KFixup](https://github.com/chunnann/ATH9KFixup) | Various patches for unsupported Atheros Wi-Fi cards
[BrightnessKeys](https://github.com/devicemanager/BrightnessKeys) | Automatic handling of brightness keys based on ACPI Specification
[BlueToolFixup](https://github.com/devicemanager/BrcmPatchRAM) | Forces BlueTool to skip attempting a firmware update, allowing for some Broadcom chipsets to work on Monterey. It also properly sets the transport
[CPUFriend](https://github.com/devicemanager/CPUFriend) | Dynamic power management data injection
[CpuTscSync](https://github.com/devicemanager/CpuTscSync) | Сombining functionality of VoodooTSCSync and disabling xcpm_urgency if TSC is not in sync
[CryptexFixup](https://github.com/devicemanager/CryptexFixup) | Kernel extension for installing Rosetta Cryptex in macOS Ventura
[DebugEnhancer](https://github.com/devicemanager/DebugEnhancer) | Enable debug output in the macOS kernel
[DiskArbitrationFixup](https://github.com/Goldfish64/DiskArbitrationFixup) | Disable the uninitialised disk message at disk insertion
[ECEnabler](https://github.com/1Revenger1/ECEnabler) | Allows reading Embedded Controller fields over 1 byte long, vastly reducing the amount of ACPI modification needed (if any) for working battery status
[HibernationFixup](https://github.com/devicemanager/HibernationFixup) | Enable 3 & 25 mode hibernation on certain hardware
[Innie](https://github.com/cdf/Innie) | Making PCIe drives appear as internal
[IntelBTPatcher](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Fix Intel Bluetooth on Big Sur, Catalina, Mojave, High Sierra etc, tested with Big Sur and Catalina all working good.
[Kryptonite](https://github.com/mayankk2308/kryptonite) | Various patches for Thunderbolt-based eGPUs
[MacHyperVSupport](https://github.com/devicemanager/MacHyperVSupport) | Hyper-V integration services for macOS
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | Disables Touch ID checks causing hangs
[NVMeFix](https://github.com/devicemanager/NVMeFix) | Improved power management for generic NVMe SSDs
[OpcodeEmulator](https://www.insanelymac.com/forum/topic/329704-opcode-emulator-opemu-plug-in-project/) | Intel Haswell Pentium / Celeron Series Or older processor expansion instruction set Emulation
[RestrictEvents](https://github.com/devicemanager/RestrictEvents) | Blocking unwanted processes causing compatibility issues on different hardware
[RealtekCardReaderFriend](https://github.com/0xFireWolf/RealtekCardReaderFriend) | Recognize Realtek card readers as native ones
[RTCMemoryFixup](https://github.com/devicemanager/RTCMemoryFixup) | Offsets in CMOS (RTC) memory emulation
[FeatureUnlock](https://github.com/devicemanager/FeatureUnlock) | Enabling Sidecar support and other
[SystemProfilerMemoryFixup](https://github.com/Goldfish64/SystemProfilerMemoryFixup) | Show memory tab on MacBook models with soldered RAM
[ThunderboltReset](https://github.com/osy86/ThunderboltReset) | Disable the ICM in the Alpine Ridge
[VirtualSMC](https://github.com/devicemanager/VirtualSMC) | Advanced SMC emulation
[WhateverGreen](https://github.com/devicemanager/WhateverGreen) | Various patches necessary for GPUs

Plugins which functionality was merged into other plugins:

| Name | Short description |
|:-----|:------------------|
[AzulPatcher4600](https://github.com/coderobe/AzulPatcher4600) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[AppleBacklightFixup](https://github.com/hieplpvip/AppleBacklightFixup) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[EnableLidWake](https://github.com/syscl/EnableLidWake) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[BrcmWLFixup](https://github.com/PMheart/BrcmWLFixup) | Superseded by [AirportBrcmFixup](https://github.com/lvs1974/AirportBrcmFixup)
[BT4LEContinuityFixup](https://github.com/devicemanager/BT4LEContinuityFixup) | Superseded by [OpenCore](https://github.com/devicemanager/OpenCorePkg)  `ExtendBTFeatureFlags` quirk
[CoreDisplayFixup](https://github.com/PMheart/CoreDisplayFixup) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[CpuTopologySync](https://github.com/devicemanager/CpuTopologySync) | Superseded by [OpenCore](https://github.com/devicemanager/OpenCorePkg)  `ProvideCurrentCpuInfo` quirk
[MacProMemoryNotificationDisabler](https://github.com/IOIIIO/MacProMemoryNotificationDisabler) | Superseded by [RestrictEvents](https://github.com/devicemanager/RestrictEvents)
[NoVPAJpeg](https://github.com/vulgo/NoVPAJpeg) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[NightShiftUnlocker](https://github.com/Austere-J/NightShiftUnlocker) | Superseded by [FeatureUnlock](https://github.com/devicemanager/FeatureUnlock)
[NightShiftEnabler](https://github.com/cdf/NightShiftEnabler) | Superseded by [FeatureUnlock](https://github.com/devicemanager/FeatureUnlock)
[IntelGraphicsDVMTFixup](https://github.com/BarbaraPalvin/IntelGraphicsDVMTFixup) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[IntelGraphicsFixup](https://github.com/lvs1974/IntelGraphicsFixup) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[NvidiaGraphicsFixup](https://github.com/lvs1974/NvidiaGraphicsFixup) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[Shiki](https://github.com/devicemanager/Shiki) | Superseded by [WhateverGreen](https://github.com/devicemanager/WhateverGreen)
[SidecarEnabler](https://github.com/hieplpvip/SidecarEnabler) | Superseded by [FeatureUnlock](https://github.com/devicemanager/FeatureUnlock)
