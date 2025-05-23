# Slides Remote :video_game:

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)

WIFI Presentation Remote - Control Slides (like: MS PowerPoint) from your Android Phone.

## Features :dart:

- [x] Free & Open Source
- [x] Very Easy to use
- [x] No Internet connection required
- [x] Multi Platform App (We write once & you Run anywhere!)
- [x] You Can also Control your PC Slides anywhere in the world! (in this case you need Internet connection)
- [x] Control the Start, Stop, Next, Back of your presentation
- [x] <del>Control the Computer Volume (UP/Down/Mute)</del>

# Thank _You_!

Please :star: this repo to help us improve the quality.

## Screenshots

|                      Home                      |            Scan Server IP :camera:             |
| :--------------------------------------------: | :--------------------------------------------: |
|      ![screenshoot](Screenshots/home.jpg)      | ![screenshoot](Screenshots/scan_server_ip.jpg) |
|                 Remote Control                 |                   Server App                   |
| ![screenshoot](Screenshots/remote_control.jpg) |     ![screenshoot](Screenshots/server.PNG)     |

## Requirements

- Java 11+
- Computer & Phone connected on the same wireless (no internet required).

## Languages & Tools

- Android App :iphone:
  - Java
  - Card View (Material Design)
- Desktop App (Server) :computer:
  - JavaFX
  - JFoenix (Material design)
  - Ikonli (Icons)
- Zxing (QRCode Generator & Reader)
- Socket (Communication)

## Installation

Pre-requisite: Java installed

1. Download the apk and jar file from Releases.
2. Transfer the apk file to your Android device and install it.
3. Run the server with: `java -jar SlidesRemote-Server-1.0-SNAPSHOT.jar`
4. Run the android app and connect to the server.

## Building (server)

Pre-requisite: Maven

1. `git clone https://github.com/jchai01/slides-remote.git`
2. `cd SlidesRemote-Server` & run `mvn package`

## Building (app)

1. Open SlidesRemote project on Android Studio.

## Contributing 💡

If you want to contribute to this project and make it better with new ideas, your pull request is very welcomed.
If you find any issue just put it in the repository issue section, thank you.
