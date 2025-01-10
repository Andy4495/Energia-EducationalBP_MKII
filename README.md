# Energia-Educational BoosterPack MKII Examples Library

[![Arduino Compile Sketches](https://github.com/Andy4495/Energia-EducationalBP_MKII/actions/workflows/arduino-compile-sketches.yml/badge.svg)](https://github.com/Andy4495/Energia-EducationalBP_MKII/actions/workflows/arduino-compile-sketches.yml)
[![Check Markdown Links](https://github.com/Andy4495/Energia-EducationalBP_MKII/actions/workflows/check-links.yml/badge.svg)](https://github.com/Andy4495/Energia-EducationalBP_MKII/actions/workflows/check-links.yml)

This repo is packaged as an Arduino library in order to access the EducationalBP_MKII examples that are included as part of the [Energia application][1]. It is not actually a library, but includes an `examples` folder so that Arduino will load the files and display the examples.

Because these examples are included in the Energia application itself, they are not available when loading [Texas Instruments platform cores][5] into Arduino using the Boards Manager. I have therefore packaged them as a library so that they can be loaded into Arduino and be accessible through the `File->Examples->Energia-EducationalBP_MKII` menu.

## Installation

This library can be installed using the Arduino Library Manager with the library name `Energia-EBP_MKII`.

## Usage

The example sketches are available from the `File->Examples->Energia-EBP_MKII` menu.

## Documentation

The Energia website has an [overview][6] of the Educational BoosterPack, and tutorials for several of the example sketches.

In case the Energia website goes offline, the overview and tutorial files are also available in the [`extras/docs`][8] directory in this repository. These files are also available in the [energia.nu][9] GitHub repo which contains the source files for the energia.nu website.

## License

Some of the files are copyright (c) Rei Vilo and licensed per [CC = BY SA NC][4].

Other files specify that they are in the public domain.

For the other files/directories that do not mention a specific license, it is assumed that they are licensed per the Energia [license.txt file][3], in which libraries and cores are covered by the [GNU LGPL v2.1][102].

Please reference [`license.txt`][101] or the specific files for more details on the license.

[1]: https://energia.nu
[3]: https://github.com/energia/Energia/blob/master/license.txt
[4]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[5]: https://github.com/Andy4495/TI_Platform_Cores_For_Arduino
[6]: https://energia.nu/guide/tutorials/boosterpacks/tutorial_edumkii/
[8]: ./extras/docs/
[9]: https://github.com/energia/energia.nu
[101]: ./license.txt
[102]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html
[//]: # ([200]: https://github.com/Andy4495/Energia-EducationalBP_MKII)
[//]: # ([10]: https://github.com/Andy4495/Energia-EducationalBP_MKII/releases)

[//]: # (This is a way to hack a comment in Markdown. This will not be displayed when rendered.)
