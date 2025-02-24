# ESP32S3-MultiMedia

A portable multimedia device based on the ESP32-S3 microcontroller with a touch screen interface and multiple integrated peripherals.

## Project Overview

ESP32S3-MultiMedia combines hardware and software to create a smartphone-like experience with a range of applications accessible through a touch interface. The project demonstrates the capabilities of the ESP32-S3 for multimedia applications and sensor integration.

## Features

- **Touch Screen Interface**: Intuitive app-based navigation system
- **Camera Integration**: Capture and save photos to SD card
- **Gallery Application**: Browse and view saved images
- **Health Monitoring**: Real-time heart rate sensing with graphical display
- **Audio Playback**: Music player for files stored on SD card
- **Wi-Fi Connectivity**: Connect to local networks
- **RGB LED Control**: Interactive sliders for color manipulation
- **Sound Effects**: Built-in beeper functionality

## Hardware Components

- ESP32-S3 microcontroller
- Camera module
- Heart rate sensor
- Audio amplifier
- Dual speakers
- Touch screen display
- SD card reader
- RGB LED
- Beeper

## Software

- Written in C++ using PlatformIO
- App-based interface design
- File system management for SD card
- Sensor data processing
- Audio playback handling
- Touch input management

## Applications

1. **Camera App**: Take photos and save them to SD card
2. **Gallery App**: View and manage saved photos
3. **Health App**: Monitor heart rate with visual graph display
4. **Music App**: Play audio files from SD card
5. **LED Control App**: Adjust RGB LED colors through interactive sliders
6. **Sound App**: Play various tones through the beeper

## Prerequisites

- PlatformIO IDE
- Required libraries (see `platformio.ini`)
- ESP32-S3 development environment

## Installation

1. Clone the repository:
```bash
git clone https://github.com/stiangglanda/ESP32S3-MultiMedia.git
cd ESP32S3-MultiMedia
```

2. Open the project in PlatformIO

3. Install required dependencies

4. Build and upload to your ESP32-S3 device

## Usage

1. Power on the device
2. Use the touch screen to navigate between apps
3. Follow on-screen instructions for each application

## Future Improvements

- [ ] Bluetooth connectivity
- [ ] Video recording capability
- [ ] Additional sensor integrations
- [ ] Cloud connectivity for data storage
- [ ] Battery optimization

## Acknowledgments

- ESP32-S3 documentation and community
- PlatformIO development environment
- Various open-source libraries used in the project
