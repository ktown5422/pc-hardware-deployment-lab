# Photo and Evidence Register

[Back to the project overview](../README.md)

## Available sources

| Source | Available material | Use in this update |
| --- | --- | --- |
| Owner's lab report | Completed assembly, front-fan power/RGB wiring, DRAM troubleshooting, BIOS hardware detection, and AMD fTPM enabled; OS installation not completed | Establishes the reported completed-work scope and OS status |
| Retained history from **Learn Computer Repair** | Text summaries of RAM reseating/display recovery, hardware inventory, and selection of Rocky Linux Desktop | Supplies the recorded inventory and troubleshooting narrative |
| Twelve owner-provided photos | Two batches provided November 10, 2026; files listed below | Reviewed evidence of assembly stages, PSU cable identification/installation, front-fan/case wiring, and a boot-device prompt |
| Existing repository | Original README at commit `134c24f05a544aa39d330fc719a8065753044cf8` | Baseline for the documentation update; its Windows deployment wording was corrected |

Twelve photos are now included in `images/` and captioned in the [photo gallery](photo-gallery.md). Repository copies retain the original filenames and image content. Embedded location and other capture metadata were removed; orientation was preserved. The source files were left unchanged.

The early interior photos show empty DIMM and expansion slots, while the rear chassis photos show an open PSU bay. A separate photo shows the PSU mounted, and another shows a boot-device message. The earlier states do not contradict the later completed-build report, but they do not independently establish the final configuration. The date above records when the photos were supplied, not when the pictured work occurred.

## Included photographs

| ID | File | Visible evidence | Limits |
| --- | --- | --- | --- |
| ASM-01 | [IMG_0323.jpeg](../images/IMG_0323.jpeg) | Mounted AORUS motherboard and AMD cooler | RAM and expansion slots empty; CPU model hidden by cooler |
| FAN-01 | [IMG_0324.jpeg](../images/IMG_0324.jpeg) | Three front fans and loose case wiring | Final fan power/lighting paths not traceable |
| CASE-01 | [IMG_0325.jpeg](../images/IMG_0325.jpeg) | Rear I/O, fan grille, slot covers, open PSU bay | Early chassis state; final PSU/GPU installation not shown |
| PWR-01 | [IMG_0326.jpeg](../images/IMG_0326.jpeg) | Loose leads with `20+4`, CPU, and PCI-E labels | Cable identification, not final connections |
| ASM-02 | [IMG_0327.jpeg](../images/IMG_0327.jpeg) | Main ATX connector attached; additional leads routed across the board | RAM and expansion slots empty; some leads loose |
| FAN-02 | [IMG_0328.jpeg](../images/IMG_0328.jpeg) | Loose case connectors beside front fans | RGB standard, pinout, and final connection not established |
| CASE-02 | [IMG_8658.jpeg](../images/IMG_8658.jpeg) | Additional rear I/O/chassis view | Open PSU bay; no graphics-card output bracket |
| ASM-03 | [IMG_8659.jpeg](../images/IMG_8659.jpeg) | Wider interior view of mounted board/cooler and chassis fans | Before RAM/GPU installation and final wiring |
| CASE-03 | [IMG_8660.jpeg](../images/IMG_8660.jpeg) | Front exterior, buttons, audio jacks, USB ports marked `3.0` | Port function and internal connections not tested by a photo |
| PWR-02 | [IMG_8672.jpeg](../images/IMG_8672.jpeg) | PSU mounted in lower compartment; 80 PLUS Bronze marking visible | Full PSU model and electrical operation not established |
| PWR-03 | [IMG_8678.jpeg](../images/IMG_8678.jpeg) | Close-up of PCI-E-labelled PSU connectors | Loose cable identification, not GPU power requirement or connection |
| BOOT-01 | [IMG_8690.jpeg](../images/IMG_8690.jpeg) | Boot-device prompt displayed on monitor | Does not confirm SSD detection, disk failure, or OS installation |

## Evidence still needed

| ID | Photo or result needed | Purpose | Status |
| --- | --- | --- | --- |
| HW-01 | Final assembled PC interior | Show installed RAM, graphics card, and final cable routing | Pending |
| FAN-03 | Final front-fan power path | Identify actual header/hub and power source | Pending |
| FAN-04 | Final front-fan lighting path | Identify actual lighting standard and controller/header | Pending |
| RAM-01 | DRAM diagnostic LED during the fault | Show the labelled indicator and symptom context | Pending |
| RAM-02 | Memory installation after troubleshooting | Show DIMM population and seating | Pending |
| BIOS-01 | BIOS CPU and memory screen | Confirm exact processor string, memory total, and BIOS version if visible | Pending |
| BIOS-02 | BIOS NVMe/storage screen | Confirm detected drive model and capacity | Pending |
| BIOS-03 | AMD CPU fTPM setting | Show the exact setting label and enabled state | Pending |

When further photos become available, add a caption describing what is visible, link the file here, and update the relevant lab note. Keep reported actions, photographed states, and new test results distinct.

No OS installation screenshots, installed OS version, driver results, or OS-based test outputs are recorded. **Rocky Linux installation and Windows installation are both NOT completed.**
