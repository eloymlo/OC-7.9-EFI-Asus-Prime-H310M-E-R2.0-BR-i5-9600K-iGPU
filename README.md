# OpenCore 7.9 EFI for Asus Prime H310M-E-R2.0-BR and i5-9600K Intel UHD Graphics 630 (iGPU)
Updated version of my previous OpenCore EFI (7.8)

In this one I have fixed the issue with sound compatibility and now is more close to a genuine Mac. Changes:

"DeviceProperties-->Add-->PciRoot(0x0)/Pci(0x1F,0x3)-->layout-id-->0B000000"

1. Timeout is set to '5'
2. ShowPicker is set to 'true'
3. Verbose mode is enabled '-v'
4. HideAuxiliary is set to 'false'
5. No more need of alcid=12 due to the "layout-id = 0B000000" change under DeviceProperties.
