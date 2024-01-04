# Custom Apps for the Flipper Zero

## Introduction
The Flipper Zero Firmware (stock and the custom Xtreme Firmware I am using) are all built on C, and as such, custom apps can be made to be ran on the Flipper. 
## Docs
[Base Documentation](https://github.com/flipperdevices/flipperzero-firmware/blob/dev/ReadMe.md)

[Flipper Application Package](https://github.com/flipperdevices/flipperzero-firmware/blob/dev/documentation/AppsOnSDCard.md)
## Project Directory Structure
Custom apps built with the Flipper Application Package (FAP) and Flipper Build Tool (FBT) consist of a primary myapp.c, myapp.png, application.fam, and a directory for assets. 

### myapp.c
This C program file is the default entry point for the application (specified in application.fam). The main include for the C app to make it run on the flipper is the FURI package. 
### application.fam
The application.fam file is the app directory where all the specifications of the Flipper app are stored. Items include: app entry point, name, ID, icon, and stack size. 
