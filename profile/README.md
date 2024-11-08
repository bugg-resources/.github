![cc-by-nc-sa-shield](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)

# Bugg 

[Bugg](https://www.bugg.xyz/) is a research initiative developing a fully autonomous acoustic monitoring system.

There are two key components to Bugg:
* A **sensor device**, which records and uploads audio data in real-time _(all designs openly available)_
* A **server instance** which analyses data and presents results in a web dashboard _(coming soon)_

## Sensor device

### User guide 

For help setting up and using the Bugg device, visit https://bugg-resources.github.io/bugg-docs/.

The resources in the following pages are for those who want to dig into the technical details of Bugg (e.g., to manufacture or modify devices) and assume the reader has prior experience with embedded systems design and manufacturing.

### Hardware

The repositories which host the electrical and mechanical CAD source files are:
* [``bugg-hardware-main``](https://github.com/bugg-resources/bugg-hardware-main): main module PCB eCAD files
* [``bugg-hardware-led``](https://github.com/bugg-resources/bugg-hardware-led): led module PCB eCAD files
* [``bugg-hardware-mic``](https://github.com/bugg-resources/bugg-hardware-mic): mic module PCB eCAD files
* [``bugg-enclosure``](https://github.com/bugg-resources/bugg-enclosure): 3D CAD files for the custom enclosure and full assembly for the Bugg device including connectors, fasteners, etc.   
* [``bugg-mech-tooling``](https://github.com/bugg-resources/bugg-mech-tooling): 3D CAD files for tools to aid assembly of the device
* [``bugg-cables``](https://github.com/bugg-resources/bugg-cables): specifications for cable assemblies

### Firmware

The repositories which host the two core parts of the firmware are:
* [``buggd``](https://github.com/bugg-resources/buggd): Recording daemon
* [``buggOS``](https://github.com/bugg-resources/buggOS): Modified version of Raspberry Pi OS (along with pre-built images for flashing to the device)

The firmware hosted in [``bugg-cm4-firmware``](https://github.com/bugg-resources/bugg-cm4-firmware) is an old version which has now been deprecated.

## Commercial use

Bugg is designed primarily for non-commercial uses such as scientific research, and for these types of use-cases all our resources are free to use (CC-BY-NC-SA 4.0).

Since the device has no formal certifications (e.g., CE or UKCA), to make the hardware ready for commercial deployments significant further investment and potentially design changes may be required.

If you have the relevant expertise and are still interested in commercial licensing options, please contact Sarab Sethi at Imperial College London.

## Publications

The below publications provide a useful overview of the motivation and philosophy of the project.

However, please be aware that the technical implementations of early prototypes differ significantly from the designs in these GitHub repositories (which are kept up to date). 

**Robust, real-time and autonomous monitoring of ecosystems with an open, low-cost, networked device.**
Sethi SS, Ewers RM, Jones NS, Orme CDL, Picinali L. Methods Ecol Evol. 2018; 9: 2383–2387. https://doi.org/10.1111/2041-210X.13089 

**SAFE Acoustics: An open-source, real-time eco-acoustic monitoring network in the tropical rainforests of Borneo.**
Sethi SS, Ewers RM, Jones NS, Signorelli A, Picinali L, Orme CDL. Methods Ecol Evol. 2020; 11: 1182–1185. https://doi.org/10.1111/2041-210X.13438

## Team

Bugg was founded and is led by [Dr. Sarab Sethi](https://profiles.imperial.ac.uk/sarab.sethi) (Imperial College London). 

Significant technical development has been undertaken by Monad Gottfried, UP Creative, and JBOTS and key academic collaborators include Prof. Robert Ewers, Prof. Nick Jones, Dr. Lorenzo Picinali, and Dr. David Orme. 

## Funding

We would like to thank [NERC](https://www.ukri.org/councils/nerc/), [EPSRC](https://www.ukri.org/councils/epsrc/), and the [Cambridge Centre for Data-Driven Discovery](https://www.c2d3.cam.ac.uk/) for their funding contributions.

If you would like to contribute direct or in-kind funding to the Bugg project, please contact Sarab. 
