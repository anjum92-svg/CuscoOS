# CuscoOS

A privacy-focused Android ROM project for
Motorola Edge 50 Fusion.

## Target

- Model: XT2429-2 (regional compatibility pending)
- Device codename: cuscoi
- SoC: Qualcomm Snapdragon 7s Gen 2
- Initial base: LineageOS 22.2 / Android 15
- Product target: lineage_cuscoi

## Project status

Early development. Source validation only.
No bootable ROM has been produced or tested.

## Privacy and security goals

- Minimal preinstalled applications
- Privacy-conscious permission defaults
- Preserve SELinux enforcement and app sandboxing
- Preserve encryption and Verified Boot where supported
- Document source revisions and security updates

CuscoOS is an independent project inspired by
privacy-focused Android design. It is not an
official GrapheneOS port or an official Motorola ROM.

## Upstream source

Device:
https://github.com/Motorola-Parrot/android_device_motorola_cuscoi/tree/lineage-22.2

Common device tree:
https://github.com/Motorola-Parrot/android_device_motorola_sm7435-common/tree/lineage-22.2

Kernel:
https://github.com/Motorola-Parrot/android_kernel_motorola_sm7435/tree/lineage-22.2

Vendor:
https://github.com/Motorola-Parrot/proprietary_vendor_motorola_cuscoi/tree/lineage-22.2

## Milestones

- [x] Repository created
- [x] Initial upstream source investigation
- [ ] Validate complete source dependencies
- [ ] Establish a reproducible build environment
- [ ] Compile the first ROM
- [ ] Test device functionality and security
- [ ] Prepare a signed development release

## Safety

Do not flash development images yet.
Do not disable encryption, SELinux, or Verified Boot
to work around build errors.
