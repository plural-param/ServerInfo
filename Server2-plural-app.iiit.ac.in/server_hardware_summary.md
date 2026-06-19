# HP Z2 Tower G1i Workstation Desktop PC — Full Hardware Summary

---

## 1. System Information

| Field | Value |
|---------|---------|
| Manufacturer | HP |
| Product Name | HP Z2 Tower G1i Workstation Desktop PC |
| Version | SBKPFV3 |
| Serial Number | 4CE539BSQM |
| SKU Number | CC9N5PA#ACJ |
| Family | 103C_53335X HP Workstation |
| UUID | 5bd27973-6e30-4c74-873e-6c0b67af3fe2 |
| Boot Status | No errors detected |

Source: :contentReference[oaicite:0]{index=0}

---

## 2. Chassis Information

| Field | Value |
|---------|---------|
| Manufacturer | HP |
| Chassis Type | Desktop |
| Serial Number | 4CE539BSQM |
| Asset Tag | 4CE539BSQM |
| Boot-up State | Safe |
| Power Supply State | Safe |
| Thermal State | Safe |
| Security Status | None |
| Height | Unspecified |
| Number of Power Cords | Unspecified |

Source: :contentReference[oaicite:1]{index=1}

---

## 3. Motherboard Information

| Field | Value |
|---------|---------|
| Manufacturer | HP |
| Product Name | 8D3C |
| Version | KBC Version 14.17.01 |
| Serial Number | PVCMN0ACYL74H3 |
| Type | Motherboard |
| Features | Hosting Board |

Source: :contentReference[oaicite:2]{index=2}

---

## 4. PCIe Slot Details

| Slot | Designation | PCIe Type | Physical Width | Usage | Height | Notes |
|--------|--------|--------|--------|--------|--------|--------|
| SLOT1 | PCIe5 x16 | PCIe 5.0 x16 | x16 | In Use | Full Height | Primary GPU Slot |
| SLOT2 | PCIe4 x4(1) | PCIe 4.0 x1 | x1 | Available | Full Height | Expansion Card Slot |
| SLOT3 | PCIe4 x16(4) | PCIe 4.0 x4 | x4 | Available | Full Height | Secondary Long Slot |
| SLOT4 | PCIe4 x4 | PCIe 4.0 x4 | x4 | Available | Full Height | Expansion Slot |
| SLOT5 | Wireless | PCIe 4.0 x1 | x1 | In Use | Other | Wireless Adapter |
| SLOT6 | M.2 SSD1 | PCIe 5.0 x4 | x4 | In Use | Other | NVMe SSD Installed |
| SLOT7 | M.2 SSD2 | PCIe 4.0 x4 | x4 | Available | Other | Empty NVMe Slot |
| SLOT8 | M.2 SSD3 | PCIe 4.0 x4 | x4 | Available | Other | Empty NVMe Slot |

Source: :contentReference[oaicite:3]{index=3}

---

## 5. PCIe Slot Availability Summary

| Resource | Available | In Use |
|-----------|-----------|---------|
| PCIe x16 Slot | 1 (SLOT3 - x4 electrical) | 1 (SLOT1 - x16 electrical) |
| PCIe x4 Slot | 1 (SLOT4) | 0 |
| PCIe x1 Slot | 1 (SLOT2) | 1 (SLOT5 Wireless) |
| M.2 NVMe Slots | 2 (SLOT7, SLOT8) | 1 (SLOT6) |

Source: :contentReference[oaicite:4]{index=4}

---

## 6. Onboard Devices

| Device | Type | Status | Bus Address |
|----------|----------|----------|----------|
| Onboard IGD | Video | Enabled | 0000:00:02.0 |
| Integrated Graphics Memory | Video | Enabled | 128 MB |

Source: :contentReference[oaicite:5]{index=5}

---

## 7. GPU Compatibility Assessment (RTX 3090)

| Requirement | System Capability | Result |
|------------|------------------|---------|
| Full-height GPU Support | Yes | ✅ |
| PCIe x16 Slot | Yes (PCIe 5.0 x16) | ✅ |
| Desktop Chassis | Yes | ✅ |
| Additional Expansion Slots | Available | ✅ |
| PSU Capacity | Not Provided | ⚠️ Verify |
| GPU Power Connectors | Not Provided | ⚠️ Verify |

### Observations

- This is a **tower workstation**, not a 1U server.
- It includes a **full-height PCIe 5.0 x16 slot**, suitable for modern GPUs.
- Physically, an RTX 3090 is much more likely to fit in this system than in the HPE DL20 Gen10 Plus.
- Before installing an RTX 3090, verify:
  - Power supply wattage (recommended 750W–1000W minimum)
  - Availability of 2× or 3× 8-pin PCIe power connectors
  - Internal clearance for a 300–330 mm GPU

Source: :contentReference[oaicite:6]{index=6}

---

## 8. Overall Summary

| Component | Details |
|-----------|---------|
| System Model | HP Z2 Tower G1i Workstation Desktop PC |
| Form Factor | Tower Workstation |
| PCIe x16 GPU Slot | 1 × PCIe 5.0 x16 (currently in use) |
| Additional PCIe Slots | 3 |
| M.2 NVMe Slots | 3 total (1 occupied, 2 available) |
| GPU Upgrade Potential | High |
| RTX 3090 Physical Compatibility | Likely Yes |
| PSU Verification Required | Yes |

