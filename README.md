# Raspberry Pi 3 powered touchscreen kiosk

- [Introduction](#introduction)
  - [Scope](#scope)
  - [Audience](#audience)
  - [Documentation](#documentation)
  - [Acronyms](#acronyms)
- [1. Components](#1-components)
- [2. Milestones (Roadmap)](#2-milestones-roadmap)
- [3. Modifications on the OS](#3-modifications-on-the-os)
- [Appendix](#appendix)
  - [Useful webpages](#useful-webpages)

## Introduction

### Scope

This repository shows the work in progress of the TI project summer 2018 no. 6. 

### Audience

This document should be a guide for future participants in the project. 

### Documentation

* [Automatic TOC generation](http://tableofcontent.eu/)
* [General form](https://docs.gitlab.com/ee/user/markdown.html)
* [Table generator](http://www.tablesgenerator.com/markdown_tables)
* Markdown editor 
	- Windows & Linux: [Ghostwriter](https://wereturtle.github.io/ghostwriter/)
	- MacOS: [Macdown](https://macdown.uranusjr.com/)

### Acronyms

**OS** Operating System

## 1. Components


| Unit         | Component                                                                          |
|:-------------|:----------------------------------------------------------------------------------:|
| Compute unit | Raspberry Pi 3 B                                                                   |
| Screen       | [Waveshare 10.1" HDMI LCD(H)](https://www.waveshare.com/wiki/10.1inch_HDMI_LCD_(H))|
| OS           | [Raspbian Stretch](https://www.raspberrypi.org/downloads/raspbian/)                |

## 2. Milestones (Roadmap)

- [x] Building development system
- [x] Putting touchscreen into operation
- [ ] Creating standby logic
    - [ ] Concept
    - [ ] Design
    - [ ] Test
- [ ] Hosting a fullscreen application
	- [ ] Design a testing application
	- [ ] Integration
- [ ] Adding a hideable virtual keyboard
- [ ] Hosting a website
	- [x] Choosing a browser
	- [ ] Adding Forward, Back and Home buttons to the fullscreen browser
	- [ ] Locking access to unwanted websites
- [ ] Integrating admin access  
...

## 3. Modifications on the OS

Mods on the OS can be found in [this](documentation/mods.md) document.

## Appendix

### Useful webpages
  
[Add a power button to the Raspberry](https://howchoo.com/g/mwnlytk3zmm/how-to-add-a-power-button-to-your-raspberry-pi)  
[Automatically disappearing virtual keyboard](https://raspberrypi.stackexchange.com/questions/61142/how-to-make-onscreen-keyboard-automatically-pop-up-when-entering-input-field)  
[Original project descripton (DE)](http://www.netzmafia.de/skripten/hardware/RasPi/Projekt-Kiosk/)  
[Pi 3 Kiosk (DE)](https://itrig.de/index.php?/archives/2309-Raspberry-Pi-3-Kiosk-Chromium-Autostart-im-Vollbildmodus-einrichten.html)  
[Various Information on the Raspberry Pi (DE)](http://www.elektronik-kompendium.de/sites/raspberry-pi/index.htm)  

