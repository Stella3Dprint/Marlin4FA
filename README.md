# 3D Printer Firmware for FA series

This is a firmware for 3D Printer of Stellamove

## Installing Marlin4FA
To install Marlin4FA on your printer you’ll first need to Download Marlin4FA, then use an IDE to Compile the Marlin4FA into a binary form and Upload it to your board. Download Marlin4FA source code on the [Github page](https://github.com/Stella3Dprint/Marlin4FA)

![code-download](https://user-images.githubusercontent.com/96027590/201231269-d0831c81-cec1-48bd-857d-7fd5992c89c3.jpg)

## Building Marlin4FA
To build Marlin4FA you'll need [Visual Studio Code](https://code.visualstudio.com/) and [PlatformIO](https://docs.platformio.org/en/latest//integration/ide/index.html#platformio-ide). PlatformIO extension turns Visual Studio Code into a complete IDE for compiling and developing Marlin4FA.

![platformio](https://user-images.githubusercontent.com/96027590/201231915-123c4b9e-d77b-4580-8255-166d72dccea6.jpg)

### 1. Install Visual Studio Code
Visit the [Visual Studio Code](https://code.visualstudio.com/) page to download and install the latest Visual Studio Code for your particular platform.

### 2. Install PlatformIO extension
Head over to the [Get PlatformIO IDE](https://platformio.org/install/ide?install=vscode) page to learn how to install PlatformIO IDE in VSCode.

### 3. Open Marlin4Pitta in Visual Stdio Code with PlatformIO
You can open Marlin in Visual Studio Code by use the Open Folder command in the Visual Stdio Code's File menu.

### 4. Build, Clean
Use the bottom Status Bar icons to build or clean.

![build](https://user-images.githubusercontent.com/96027590/201232252-913372ad-0185-4c87-98f3-ee3b708487b9.jpg)

## Upload firmware to 3D printer
3D printer require the firmware.bin file to be copied onto the onboard SD card, and then you must reboot the printer to complete the install. Firmware binary file is located in the ".pio/build/(your target board)/" folder.

![build](https://user-images.githubusercontent.com/96027590/201237400-b698bfbf-5811-412e-b134-6cc9d9d859e0.jpg)

1. Prepare SD card formated.
2. Copy the firmware binary file to the root of the SD card.
3. Ensure that the name of the file was not previously used to update the 3D printer.
4. Turn off the 3D printer, and insert the SD card.
5. Turn on the 3D printer, the upload firmware process will start automatically.



