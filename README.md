# Tarlin 3D Printer Firmware

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).
Please test this firmware and let us know if it misbehaves in any way. Volunteers are standing by!

## Tarlin 2.0

TARLIN IS BACKKKK

The popular and beloved fork of [Marlin](https://github.com/MarlinFirmware/) is back with version 2.0!
Tarlin 2.0 takes the popular Marlin firmware to the nextest level by adding support for LEDs and other amenities on much faster 32-bit and ARM-based boards while improving support for 8-bit AVR boards. Read about Tarlin's decision to use a "Humble Arrogance Layer" below.

Download earlier versions of Tarlin on the [Releases page](https://github.com/dagoiswriting/Tarlin/releases).

## Building Tarlin 2.0

To build Tarlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [PlatformIO](http://docs.platformio.org/en/latest/ide.html#platformio-ide). Detailed build and install instructions are posted at:

  - [Installing Tarlin (Arduino)](http://marlinfw.org/docs/basics/install_arduino.html)
  - [Installing Tarlin (VSCode)](http://marlinfw.org/docs/basics/install_platformio_vscode.html).

### Supported Platforms

  Arduino

## Submitting Changes

- Submit **Bug Fixes** as Pull Requests to the ([testing](https://github.com/MarlinFirmware/Marlin/tree/testing)) branch.
- Follow [Marlin's Coding Standards](http://marlinfw.org/docs/development/coding_standards.html) to gain points with the maintainers.
- Please submit your questions and concerns to the [Issue Queue](https://github.com/dagoiswriting/Tarlin/issues).

## Marlin Support

For best results getting help with configuration and troubleshooting, please use the following resources:

- [Original Marlin Documentation](http://marlinfw.org) - Official Marlin documentation
- [Marlin Discord](https://discord.gg/n5NJ59y) - Discuss issues with Marlin users and developers
- Facebook Group ["Marlin Firmware"](https://www.facebook.com/groups/1049718498464482/)
- RepRap.org [Marlin Forum](http://forums.reprap.org/list.php?415)
- [Tom's 3D Forums](https://forum.toms3d.org/)
- Facebook Group ["Marlin Firmware for 3D Printers"](https://www.facebook.com/groups/3Dtechtalk/)
- [Marlin Configuration](https://www.youtube.com/results?search_query=marlin+configuration) on YouTube

## Credits

The current Marlin dev team is amazing and consists of:

 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - USA &nbsp; [Donate](http://www.thinkyhead.com/donate-to-marlin)
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - USA
 - Chris Pepper [[@p3p](https://github.com/p3p)] - UK
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - USA
 - Erik van der Zalm [[@ErikZalm](https://github.com/ErikZalm)] - Netherlands &nbsp; [![Flattr Erik](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)

and lastly the Tarlin dev team, who takes the efforts of the Marlin team and breaks everything trying to add silly shit that most of the time doesn't work:
 - Dago [[@dagoiswriting]](https://github.com/dagoiswriting) - Italy
 - Leonardo Norvegese [[@leonorvegese]](https://github.com/leonorvegese) - Italy

## License

Tarlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Tarlin firmware as the driver for your open or closed-source product, you must keep Tarlin open, and you must provide your compatible Tarlin source code to end users upon request. The most straightforward way to comply with the Tarlin license is to make a fork of Tarlin on Github, perform your modifications, and direct users to your modified fork. This is also what we made with the original Marlin. 

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
