# Photo and Evidence Register

[Back to the project overview](../README.md)

## Available sources

| Source | Available material | Use in this update |
| --- | --- | --- |
| Owner's current instructions | Completed assembly, front-fan power/RGB wiring, DRAM troubleshooting, BIOS hardware detection, and AMD fTPM enabled; OS installation not completed | Establishes the requested completed-work scope and OS status |
| Retained history from **Learn Computer Repair** | Text summaries of the build, RAM reseating/display recovery, hardware inventory, and selection of Rocky Linux Desktop | Supplies the recorded inventory and troubleshooting narrative; original photo details remain unverified |
| Existing repository | Original README at commit `134c24f05a544aa39d330fc719a8065753044cf8` | Baseline for the documentation update; its Windows deployment wording was corrected |

The owner reports that the PC photos were shared in **Learn Computer Repair**. The history accessible for this update returned no image attachments and no older-page cursor. The supplied project folder also contained no images. **No original PC photos are included in this update, and no images have been newly inspected.**

## Photo checklist

The entries below describe evidence to recover. They are not existing files or links to missing images. A single clear photo may support more than one entry.

| ID | Photo needed | What to document after inspecting it | Status |
| --- | --- | --- | --- |
| HW-01 | Assembled PC interior | Installed components and overall cable routing | Pending original photo |
| FAN-01 | Front-fan motor power connections | Actual header/hub labels, fan leads, and any power source | Pending original photo |
| FAN-02 | Front-fan lighting connections | Actual connector type and controller/header path | Pending original photo |
| RAM-01 | DRAM diagnostic LED during the fault | LED label and visible symptom context | Pending original photo |
| RAM-02 | Memory installation after troubleshooting | DIMM population and visible seating details | Pending original photo |
| BIOS-01 | BIOS CPU and memory screen | Exact processor string, memory total, and BIOS version if visible | Pending original photo |
| BIOS-02 | BIOS NVMe/storage screen | Exact detected drive model and capacity if visible | Pending original photo |
| BIOS-03 | AMD CPU fTPM setting | Exact setting label and enabled state | Pending original photo |

## Adding recovered evidence

1. Save the relevant original photos into an `images/` directory in the repository with descriptive filenames.
2. Inspect each image and associate it with the matching ID above.
3. Add a relative Markdown link or image embed and a caption describing only what is visible.
4. Update the assembly, troubleshooting, and BIOS notes with any details the images actually establish.
5. Keep the distinction between a historical photo, a reported action, and a new test result.

No installation screenshots, installed OS version, driver results, or OS-based test outputs are currently recorded. **Rocky Linux installation and Windows installation are both NOT completed.**
