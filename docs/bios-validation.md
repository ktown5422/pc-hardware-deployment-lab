# BIOS Hardware Detection and AMD fTPM

[Back to the project overview](../README.md)

**Status: BIOS hardware checks completed and AMD CPU fTPM enabled in the lab record. OS installation is NOT completed.**

## Recorded firmware checks

| Check | Recorded result | Evidence limitation |
| --- | --- | --- |
| BIOS access and display | BIOS reached after RAM reseating and display recovery | Original BIOS photo still needed |
| CPU detection | AMD Ryzen 5 3600 recorded as detected | Exact displayed model string and readings not transcribed from an image |
| Memory detection | 16 GB DDR4 recorded in the lab notes | Exact BIOS total, slot population, speed, and timings not independently transcribed |
| Storage detection | Inland TN320 256 GB NVMe SSD recorded as detected | Exact model string and capacity reading still need the original image |
| AMD CPU fTPM | Enabled in BIOS | Setting photo still needed; OS-level validation has not been performed |

These results come from the retained **Learn Computer Repair** lab notes. The source images could not be retrieved during this update. The inventory values are retained specifications rather than newly measured results.

## AMD CPU fTPM configuration

AMD CPU fTPM was enabled during the BIOS configuration phase. This records a firmware setting only. No OS-based TPM status, version check, attestation, or encryption configuration is claimed.

## Firmware details not yet documented

- BIOS version and motherboard revision.
- Final UEFI/CSM mode, Secure Boot state, and boot order.
- Memory profile settings and operating speed.
- CPU temperature, fan RPM, and voltage readings.
- A documented reboot check showing that the fTPM setting persisted.

UEFI firmware availability is recorded in the inventory; the exact final boot configuration still needs to be captured before OS deployment.

## Next validation steps

- [ ] Add photographs showing CPU, memory, and NVMe detection.
- [ ] Add the BIOS screen showing AMD CPU fTPM enabled.
- [ ] Record the BIOS version and final boot settings.
- [ ] After an OS is installed, verify hardware recognition and TPM status using that OS.
- [ ] Record memory diagnostics, storage health, temperatures, and stability results separately.

Rocky Linux Desktop is the planned next phase. Neither Rocky Linux nor Windows has been installed, and no OS-based validation is marked complete.

Use the [evidence register](evidence.md) to connect each check to its actual photograph or test result.
