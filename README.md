
## Hardware specification

Mainboard: Gigabyte B85M-D3H
CPU: Intel i5 4570 ~ Products formerly *Haswell*
Graphic: Radeon RX580 4GB
SSD: 500GB 960EVO
HDD: 1.5TB + 500GB
RAM: 16 GB

## BIOS Configuration

Intel BIOS settings

11.1. Disable

Fast Boot
Secure Boot
VT-d (can be enabled if you set DisableIoMapper to YES)
CSM
Thunderbolt(For initial install, as Thunderbolt can cause issues if not setup correctly)
Intel SGX
Intel Platform Trust
CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable both AppleCpuPmCfgLock and AppleXcpmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)
11.2. Enable

VT-x
Above 4G decoding
Hyper-Threading
Execute Disable Bit
EHCI/XHCI Hand-off
OS type: Windows 8.1/10 UEFI Mode
DVMT Pre-Allocated(iGPU Memory): 64MB

## OpenCore notes



## SMBIOS Config

Type:         iMac14,2
Serial:       D25QD0SNF8JC
Board Serial: D25537207QXF8YLUE
SmUUID:       9D079D6B-996A-4CCE-86C9-55677D91DCDB

