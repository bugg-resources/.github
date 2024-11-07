![cc-by-nc-sa-shield](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)

# Bugg 

[Bugg](https://www.bugg.xyz/) is a fully autonomous acoustic monitoring system.

There are two key components to Bugg:
* A **sensor device**, which records and uploads audio data in real-time _(all designs available on this repository)_, and
* A **server instance** which analyses data and presents results in a web dashboard _(coming soon)_

## Sensor device

### Electronics

The repositories which host the electrical and mechanical CAD source files are:
* [``sp-hardware-main``](https://github.com/bugg-resources/bugg-hardware-main): main module PCB eCAD files
* [``sp-hardware-led``](https://github.com/bugg-resources/bugg-hardware-led): led module PCB eCAD files
* [``sp-hardware-mic``](https://github.com/bugg-resources/bugg-hardware-mic): mic module PCB eCAD files
* [``bugg-enclosure``](https://github.com/bugg-resources/bugg-enclosure): 3D CAD files for the custom enclosure and full assembly for the Bugg device including connectors, fasteners, etc.   
* [``bugg-mech-tooling``](https://github.com/bugg-resources/bugg-mech-tooling): 3D CAD files for tools to aid assembly of the device

### Firmware

The firmware running on the device, with associated documentation, can be found in [``bugg-cm4-firmware``](https://github.com/bugg-resources/bugg-cm4-firmware).

## Commercial use

Bugg is designed primarily for non-commercial uses such as scientific research. Since the device has no formal certifications (e.g., CE or UKCA), to make the hardware ready for commercial deployments significant further investment and potentially design changes may be required.

If you have the relevant expertise and are still interested in commercial licensing options, please contact Sarab Sethi at Imperial College London.

## Relevant academic publications

Whilst still a useful overview of the motivation and philosophy of the project, the resources in these GitHub repositories reflect the latest Bugg designs which differ significantly from the early prototypes outlined in these publications. 

**Robust, real-time and autonomous monitoring of ecosystems with an open, low-cost, networked device.**
Sethi SS, Ewers RM, Jones NS, Orme CDL, Picinali L. Methods Ecol Evol. 2018; 9: 2383–2387. https://doi.org/10.1111/2041-210X.13089 

**SAFE Acoustics: An open-source, real-time eco-acoustic monitoring network in the tropical rainforests of Borneo.**
Sethi SS, Ewers RM, Jones NS, Signorelli A, Picinali L, Orme CDL. Methods Ecol Evol. 2020; 11: 1182–1185. https://doi.org/10.1111/2041-210X.13438
