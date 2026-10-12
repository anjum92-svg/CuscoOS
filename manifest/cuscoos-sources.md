# CuscoOS upstream source inventory

Initial candidate: LineageOS 22.2 / Android 15
Target: Motorola Edge 50 Fusion, codename cuscoi

| Component | Repository | Branch |
|---|---|---|
| Device tree | Motorola-Parrot/android_device_motorola_cuscoi | lineage-22.2 |
| Common device tree | Motorola-Parrot/android_device_motorola_sm7435-common | lineage-22.2 |
| Kernel | Motorola-Parrot/android_kernel_motorola_sm7435 | lineage-22.2 |
| Vendor files | Motorola-Parrot/proprietary_vendor_motorola_cuscoi | lineage-22.2 |
| Android manifest | LineageOS/android | lineage-22.2 |

## Validation still required

- Confirm the device tree's complete dependency list.
- Confirm kernel and common-tree revisions are compatible.
- Confirm the exact XT2429-2 firmware and regional variant.
- Pin source revisions to immutable commit IDs.
- Confirm licensing and proprietary blob requirements.
- Compile and test before any device installation.

A branch existing is not proof that all components build together.
