# BeagleBone Black Ubuntu 22.04 BOOT

This repository contains instructions and scripts for setting up a BeagleBone Black (rev C) with Ubuntu 22.04. Follow these steps to get your BeagleBone Black up and running with the latest version of Ubuntu.

## Prerequisites

Before you begin, ensure you have the following:

- A BeagleBone Black (rev C) board
- A computer with an SD card reader
- A microSD card (16GB or higher)
- A stable internet connection

## Installation

1. Downlaod gparted app from Ubuntu software store 

2. Insert SD card using the reader into your PC

3. open gparted app 

4. Download the Ubuntu 22.04 image for BeagleBone Black from [official sources](URL).

5. Use a tool like Etcher to write the image to your microSD card.

6. Insert the microSD card into the BeagleBone Black.

7. Connect the BeagleBone Black to your computer via USB or Ethernet.

8. Power up the BeagleBone Black.

## Usage

1. Connect to the BeagleBone Black via SSH:

   ```bash
   ssh ubuntu@<BeagleBone_IP_Address>
