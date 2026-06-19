## System Hardware Summary

| Component | Value |
|------------|--------|
| Manufacturer | HPE |
| Model | ProLiant DL20 Gen10 Plus |
| Form Factor | 1U Rack Server |
| Operating System | Ubuntu 22.04.4 LTS |
| Kernel | Linux 5.15.0-177-generic |
| Architecture | x86_64 |
| BIOS Version | U60 |
| BIOS Date | 2023-10-19 |

## CPU

| Item | Value |
|--------|--------|
| Model | Intel Xeon E-2356G |
| Socket Count | 1 |
| Physical Cores | 6 |
| Threads | 12 |
| Base Frequency | 3.20 GHz |
| Max Frequency | 5.00 GHz |
| L2 Cache | 3 MB |
| L3 Cache | 12 MB |
| Virtualization | VT-x |

## Memory

| Item | Value |
|--------|--------|
| Installed RAM | 32 GB |
| Maximum Supported RAM | 128 GB |
| Memory Type | DDR4 ECC UDIMM |
| Memory Speed | 3200 MT/s |
| Error Correction | Multi-bit ECC |
| Total DIMM Slots | 4 |
| Used DIMM Slots | 2 |
| Free DIMM Slots | 2 |

### Memory Modules

| Slot | Size | Type | Speed | Manufacturer |
|--------|--------|--------|--------|--------|
| PROC 1 DIMM 1 | 16 GB | DDR4 ECC | 3200 MT/s | Samsung |
| PROC 1 DIMM 2 | Empty | - | - | - |
| PROC 1 DIMM 3 | 16 GB | DDR4 ECC | 3200 MT/s | Samsung |
| PROC 1 DIMM 4 | Empty | - | - | - |

## Storage

| Device | Model | Capacity | Type |
|----------|----------|----------|----------|
| sda | EG001200MXJQU | 1.1 TB | SAS/SATA Disk |
| sdb | VK000480GZCNE | 447.1 GB | SSD |
| Matrox G200eH3 | Embedded Video Controller | - | Graphics |

### Disk Partitions

| Partition | Size | Mount Point |
|------------|------|-------------|
| sdb1 | 1 GB | /boot/efi |
| sdb2 | 1 GB | /boot |
| sdb3 | 150 GB | / |
| sdb4 | 64 GB | Swap |
| sdb5 | 231.1 GB | /home |

### Filesystem Usage

| Mount Point | Size | Used | Available | Usage |
|-------------|------|------|-----------|-------|
| / | 150 GB | 22 GB | 123 GB | 16% |
| /home | 232 GB | 64 GB | 168 GB | 28% |
| /boot | 1 GB | 264 MB | 646 MB | 30% |
| /boot/efi | 1.1 GB | 6.1 MB | 1.1 GB | 1% |

## Graphics

| Device | Type |
|----------|----------|
| Matrox MGA G200eH3 | Embedded Server Graphics |

## PCIe Expansion

| Slot | Type | Status |
|--------|--------|--------|
| PCI-E Slot 1 | PCIe 4.0 x8 | Available |
| PCI-E Slot 2 | PCIe 4.0 x16 (x8 electrical) | Available |
| Storage Controller Slot 12 | PCIe 3.0 x4 U.2 | In Use |

## Networking

| Device | Type |
|----------|----------|
| Broadcom NetXtreme BCM5720 Port 1 | Gigabit Ethernet |
| Broadcom NetXtreme BCM5720 Port 2 | Gigabit Ethernet |

## Chassis

| Item | Value |
|--------|--------|
| Manufacturer | HPE |
| Type | Rack Mount Chassis |
| Height | 1U |
| Power Cords | 2 |
| Power Supply State | Safe |
| Thermal State | Safe |

## Motherboard

| Item | Value |
|--------|--------|
| Manufacturer | HPE |
| Model | ProLiant DL20 Gen10 Plus |
| Serial Number | PXWAAA2WGJ70GG |
| Type | Motherboard |

## BIOS

| Item | Value |
|--------|--------|
| Vendor | HPE |
| Version | U60 |
| Release Date | 2023-10-19 |
| BIOS Revision | 1.90 |
| Firmware Revision | 3.2 |

## Upgrade Summary

| Resource | Current | Maximum | Available |
|-----------|---------|----------|-----------|
| CPU | Xeon E-2356G (6C/12T) | Platform dependent | - |
| RAM | 32 GB | 128 GB | 96 GB free capacity |
| DIMM Slots | 2 Used | 4 Total | 2 Free |
| PCIe Slots | 1 Storage + 2 General | 3 Total | 2 Free |
| Storage Drives | 2 Installed | Additional depends on chassis | Available |

## Notes

- Enterprise-grade ECC memory is enabled.
- Two 16 GB Samsung DDR4-3200 ECC UDIMMs are installed.
- The server has a 1U rack chassis.
- GPU support is limited by the 1U form factor and power constraints.
- Suitable for virtualization, web hosting, databases, CI/CD, NLP services, and moderate compute workloads.
