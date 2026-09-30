# nova-smart-clock
# NOVA — Smart Ambient Clock

> A compact, polished smart clock designed to feel like a real consumer product rather than a typical electronics prototype.

## Overview

**NOVA** is an ESP32-powered smart ambient clock that combines a clean, minimal display with useful environmental information, alarms, and subtle animations.

The goal is to create a physical desk clock that looks and behaves like something you could actually buy — with a focus on **industrial design, smooth software, and a simple user experience**.

Instead of relying on a phone for basic information such as the time, temperature, or alarms, NOVA provides it through a dedicated always-visible device.

## Planned Features

### Clock

* Large digital time display
* Date and day of the week
* Multiple clock-face designs
* 12/24-hour format
* Accurate timekeeping

### Environment

* Real-time temperature
* Humidity measurement
* Simple environmental status display
* Optional future weather integration

### Alarms

* Multiple configurable alarms
* Alarm enable/disable controls
* Custom alarm behaviour
* Animated alarm screen
* Buzzer notification
* Night-friendly alarm interface

### Interface

* Physical buttons or rotary encoder
* Smooth screen transitions
* Small UI animations
* Multiple display modes
* Automatic night/dim mode
* Minimal interface designed for quick readability

### Physical Design

* Compact desktop form factor
* Custom enclosure
* Internal cable management
* Accessible controls
* Designed to look intentional and finished rather than like an exposed development board

## Hardware

The initial design is planned around an ESP32 microcontroller.

| Component                   | Purpose                 |
| --------------------------- | ----------------------- |
| ESP32                       | Main microcontroller    |
| 2–3" colour IPS display     | Main user interface     |
| Temperature/humidity sensor | Environmental readings  |
| Rotary encoder / buttons    | User controls           |
| Buzzer                      | Alarm notifications     |
| LEDs                        | Status/ambient feedback |
| USB power                   | Power source            |
| Custom enclosure            | Physical housing        |

The exact components may change during development depending on availability, compatibility, and testing.

## Software

The software will be responsible for:

* Rendering the clock interface
* Managing alarms
* Reading environmental sensors
* Handling physical controls
* Updating the display
* Running animations
* Managing display brightness/night mode
* Maintaining accurate time

The software will be developed incrementally, starting with the core clock and expanding into the more advanced features.

## Development Plan

### Phase 1 — Core Hardware

* Select and test the ESP32
* Connect the display
* Confirm reliable power
* Test physical inputs
* Test the environmental sensor

### Phase 2 — Clock Software

* Implement accurate time display
* Add date/day
* Create the initial UI
* Implement screen updates

### Phase 3 — Smart Features

* Add temperature and humidity
* Implement alarms
* Add buzzer functionality
* Add multiple clock faces
* Add night mode

### Phase 4 — Polish

* Add animated transitions
* Improve typography and spacing
* Refine the interface
* Design the enclosure
* Improve cable management and physical layout

### Phase 5 — Final Build

* Assemble the electronics
* Install the components into the enclosure
* Test all major functions
* Fix hardware/software issues
* Document the completed device

## Design Goals

NOVA is being designed around four main principles:

**1. Readability**

The time should be immediately visible from across a desk.

**2. Simplicity**

The clock should provide useful information without becoming another complicated touchscreen gadget.

**3. Polish**

Animations, typography, enclosure design and physical controls should feel intentional and cohesive.

**4. Expandability**

The ESP32 platform allows additional features and improvements to be added after the initial version.

## Why I Am Building It

Many electronics projects focus primarily on getting a circuit to work. NOVA is also an experiment in **product design**.

I want to explore how hardware, software and industrial design work together to turn a collection of electronic components into something that feels like a finished consumer product.

The project will involve electronics, embedded programming, UI design, CAD/enclosure design and iterative testing.

## Current Status

**Status:** 🟡 Design / Planning

The initial hardware architecture and feature set are being developed.

Future updates will document the project from the first prototype through to the final assembled clock.

## Project Documentation

Development documentation will be added to this repository as the project progresses.

Planned documentation includes:

* Hardware schematics
* Parts list
* Wiring diagrams
* Software architecture
* UI designs
* CAD/enclosure files
* Prototype photos
* Testing results
* Development notes
* Final build documentation

## Future Ideas

Features that may be explored after the initial version include:

* Wi-Fi weather information
* Additional clock faces
* Sunrise/sunset information
* Custom alarms
* Web-based configuration
* OTA firmware updates
* More advanced animations
* Ambient light sensing
* Automatic brightness adjustment

These features are secondary to the core goal of creating a reliable and polished clock.

## Project Structure

```text
nova-smart-clock/
│
├── README.md
│
├── src/
│   └── main.cpp
│
├── hardware/
│   ├── schematic/
│   └── parts-list.md
│
├── cad/
│   └── enclosure/
│
├── ui/
│   └── designs/
│
├── documentation/
│   └── development-log.md
│
└── media/
    └── photos/
```

## License

This project is primarily a personal hardware and software development project.

License details will be added once the project reaches a stable release.
