# Virtual Pet Simulator

A terminal-based virtual pet simulation developed in C, focused on interactive state management, dynamic behavior, and event-driven systems.

The user creates and names their own virtual pet, then interacts with it through a command-line interface. Every interaction can affect the pet's internal state, creating a small simulation environment that evolves throughout the session.

## Overview

The virtual pet maintains a set of dynamic attributes that represent its current state:

* Health
* Hunger
* Energy
* Happiness
* Mood

The pet's state changes based on user actions and, as development progresses, time and random events.

## Planned Features

* Custom pet creation and naming
* Interactive terminal interface
* Dynamic state management
* Pet actions and interactions
* Mood and behavior system
* Random events
* Time-based state changes
* Save and load functionality
* Modular C architecture

## Technical Focus

The project is designed to provide practical experience with core C programming concepts, including:

* Variables and data types
* Conditional logic
* Loops
* Functions
* Arrays and strings
* Structures (`struct`)
* Modular programming
* File I/O
* Random number generation
* Time handling
* State management
* Event-driven logic

## Architecture

The project is structured around separating the pet's state and simulation logic from the user interface.

```text
User Input
    ↓
Command System
    ↓
Pet State
    ↓
Simulation Logic
    ├── Actions
    ├── Mood System
    ├── Random Events
    └── Time-Based Updates
    ↓
Save / Load
```

This approach allows the simulation logic to evolve independently from the terminal interface.

## Embedded Systems Direction

Although the current project is designed as a terminal-based simulation, its architecture is intended to provide a foundation for a future embedded implementation.

The same state-management and control logic could later be adapted to an ESP32-based system using physical inputs and outputs such as:

* Buttons
* Sensors
* LEDs
* Displays
* Buzzers

```text
Terminal Simulation
        ↓
Pet State & Control Logic
        ↓
Embedded Implementation
        ↓
ESP32 + Sensors + Outputs
```

## Development Status

**In Development**

The simulator is being developed incrementally, with new functionality introduced as different C programming and software design concepts are implemented.

## Project Goals

The primary goal is to build a complete C project while developing practical experience with program structure, state management, event-driven logic, file handling, and systems-oriented programming.

A secondary goal is to create an architecture that can later be explored in an embedded systems environment.
