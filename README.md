# ClassicWB P96 Package

ClassicWB P96 is a feature rich Workbench enhancement by Bloodwych targeted UAE emulator using 16-32bit colour screenmodes and NewIcons.

## Description

ClassicWB P96 Package contains ClassicWB P96 v28 created by Bloodwych from EAB.

With permission from Bloodwych it has been converted to a package for HstWB Installer.

Original version of ClassicWB P96 can be downloaded from http://classicwb.abime.net/.

## Requirements

ClassicWB P96 package can be installed on any Amiga with Amiga OS 3.2, 3.1.4 or 3.1 and about 131MB free space on a harddrive for installation.

## Installation

Download latest release from https://github.com/henrikstengaard/classicwb-p96-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure ClassicWB P96 package using defined assigns.
During installation dialogs are presented to customize ClassicWB installation.

## Assigns

Installation of ClassicWB P96 package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

ClassicWB P96 files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on S/Startup-Sequence from ClassicWB System.hdf with following changes:

- Removed Workbench installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.
- Added support for Amiga OS 3.2 and 3.1.4:
  - Reinstalled MUI to fix Scalos prefs and iGame.
  - Patched Scalos title to 3.1.4 for Oldicons enabled and disabled.
  - Added LoadModule ROMUPDATE to support Kickstart 3.1 being patched to 3.1.4.
  - Added version checking of DEVS:scsi.device, so it only will be loaded if scsi.device in memory/resident is less than v43.45.
  - Added install patch Amiga OS 3.1.4.1, if Amiga OS 3.1.4.1 update is installed.
  - Disabled Copper, BorderBlank, StackAttack.

## Screenshots

Screenshots of ClassicWB P96 from http://classicwb.abime.net/classicweb/p96pics.htm.

![ClassicWB P96 3.2 1](screenshots/classicwb_p96_3.2_1.png?raw=true)

![ClassicWB P96 3.1.4 1](screenshots/classicwb_p96_3.1.4_1.png?raw=true)

![ClassicWB P96 1](screenshots/classicwb_p96_1.png?raw=true)

![ClassicWB P96 2](screenshots/classicwb_p96_2.png?raw=true)

![ClassicWB P96 3](screenshots/classicwb_p96_3.png?raw=true)

![ClassicWB P96 4](screenshots/classicwb_p96_4.png?raw=true)

![ClassicWB P96 5](screenshots/classicwb_p96_5.png?raw=true)

![ClassicWB P96 6](screenshots/classicwb_p96_6.png?raw=true)